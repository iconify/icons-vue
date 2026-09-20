<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujzohcwsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:garage-door-open-outline-sharp" /></template>
<style>
.ujzohcwsa {
  fill: currentColor;
  d: path("M7.5 18V9h9v9v-9h-9zM6 18h1.5V9h9v9H18V8.85L12 4.5L6 8.85zm3-6h6v-1.5H9zm3-4q.425 0 .713-.288T13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8M4 20V10H.975L12 2l11 8h-3v10h-5v-6.5H9V20z");
}

</style>
