<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lei6vob2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidifier-baby" /></template>
<style>
.lei6vob2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9.5h9a1 1 0 0 1 1 1v7.25a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1V10.5a1 1 0 0 1 1-1ZM5 21.5h14M8.5 6.75c-1-1.25 1-2.75 0-4.25M12 6.75C11 5.5 13 4 12 2.5m3.5 4.25c-1-1.25 1-2.75 0-4.25M12 14.25h.01");
}

</style>
