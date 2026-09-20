<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d20glxb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-data-bar-32-regular" /></template>
<style>
.d20glxb4m {
  fill: currentColor;
  d: path("M10.5 12A1.5 1.5 0 0 0 9 13.5v9a1.5 1.5 0 0 0 3 0v-9a1.5 1.5 0 0 0-1.5-1.5m4 3.5a1.5 1.5 0 0 1 3 0v7a1.5 1.5 0 0 1-3 0zm7 2.5a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 0 3 0v-3a1.5 1.5 0 0 0-1.5-1.5M19 2c1.306 0 2.418.835 2.83 2h1.67A3.5 3.5 0 0 1 27 7.5v19a3.5 3.5 0 0 1-3.5 3.5h-15A3.5 3.5 0 0 1 5 26.5v-19A3.5 3.5 0 0 1 8.5 4h1.67A3 3 0 0 1 13 2zm-6 2a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2zM8.5 6A1.5 1.5 0 0 0 7 7.5v19A1.5 1.5 0 0 0 8.5 28h15a1.5 1.5 0 0 0 1.5-1.5v-19A1.5 1.5 0 0 0 23.5 6h-1.67A3 3 0 0 1 19 8h-6a3 3 0 0 1-2.83-2z");
}

</style>
