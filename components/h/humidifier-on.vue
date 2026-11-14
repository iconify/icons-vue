<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ps8gb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidifier-on" /></template>
<style>
.s6ps8gb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.3 19H4V8.5h8.5v7.7m.9 5.3H3V19h9.3M6.5 5.75c-1.25-1 1.25-2.25 0-3.25M10 5.75c-1.25-1 1.25-2.25 0-3.25m6 13.25a3 3 0 1 0 4 0m-2-1.25v3");
}

</style>
