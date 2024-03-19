# vue-router
vue router 

## How to use router

1 - Define the Routing Rules : router/index.ts

2 - Tell Vue About Our Rules
```javascript
# main.ts
import router from './router'
app.use(router)
```

3 - Define Where to Render the Page Components
```javascript
# App.vue
<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
    <main>
        <RouterView />
    </main>
</template>
```