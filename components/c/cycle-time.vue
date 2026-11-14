<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_g-h8b-z"/><path class="w58fw3bzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cycle-time" /></template>
<style>
.r_g-h8b-z {
  d: path("M14.071 4.273a8 8 0 0 1 0 15.454m-4.142 0a8 8 0 0 1 0-15.454");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w58fw3bzy {
  d: path("m2.5 17l1.75-3l3 1.75M21.5 7l-1.75 3l-3-1.75M12 8v4l3 1.75");
}

</style>
