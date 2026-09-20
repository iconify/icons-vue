<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar5olr4ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-file-outline-sharp" /></template>
<style>
.ar5olr4ft {
  fill: currentColor;
  d: path("M10.75 19q.95 0 1.6-.65t.65-1.6V13h3v-2h-4v3.875q-.275-.2-.587-.288t-.663-.087q-.95 0-1.6.65t-.65 1.6t.65 1.6t1.6.65M4 22V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
