<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m5r5z-_eg"/><path class="j0kecjf9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:control-room-plant" /></template>
<style>
.j0kecjf9u {
  d: path("M2.5 12a4 4 0 0 1 8 0m-4 0l2-3m8 3V8.5M19 12V6.5");
}

.m5r5z-_eg {
  d: path("M2.5 3h8v9h-8Zm11 0h8v9h-8Zm-11 13.5h19m-17 0V21m15-4.5V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
