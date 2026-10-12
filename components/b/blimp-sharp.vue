<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ux4bjxkzx"/><path class="siqwtmqng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blimp-sharp" /></template>
<style>
.siqwtmqng {
  d: path("M12.75 5c4.7 0 8.5 2.24 8.5 5s-3.8 5-8.5 5s-8.5-2.24-8.5-5s3.8-5 8.5-5Zm-1.5 9.85v2.65m3.5-2.65v2.65m-4.5 0h5.5v3h-5.5z");
}

.ux4bjxkzx {
  d: path("M3.5 4.25h.75l.55.51l2.15 1.98l.55.51v5.5l-.55.51l-2.15 1.98l-.55.51h-1.5V4.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
