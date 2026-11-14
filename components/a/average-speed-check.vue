<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sy90i8bmh"/><path class="z1rmb_fnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:average-speed-check" /></template>
<style>
.sy90i8bmh {
  d: path("M2.5 17v-2.5l2.5-.75L7 11h4.5l2 2.75l2.25.75V17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1rmb_fnq {
  d: path("M3.75 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 3h9.5v5H12Zm6.5 5v13.5");
}

</style>
