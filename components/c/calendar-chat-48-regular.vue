<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjg3ed7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-48-regular" /></template>
<style>
.fjg3ed7on {
  fill: currentColor;
  d: path("M35.001 24C41.076 24 46 28.924 46 34.999s-4.924 10.999-10.999 10.999c-1.865 0-3.663-.465-5.26-1.337l-4.52 1.302a.957.957 0 0 1-1.184-1.185l1.303-4.516A10.95 10.95 0 0 1 24 34.999C24 28.924 28.925 24 35 24m.749-18A6.25 6.25 0 0 1 42 12.25v11.793c-.78-.5-1.618-.918-2.5-1.243v-6.3h-31v19.25a3.75 3.75 0 0 0 3.75 3.75h10.553q.18.487.398.96L22.757 42H12.25A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zM31 36a1 1 0 1 0 0 2h5a1 1 0 1 0 0-2zm0-4a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2zM12.25 8.5a3.75 3.75 0 0 0-3.75 3.75V14h31v-1.75a3.75 3.75 0 0 0-3.75-3.75z");
}

</style>
