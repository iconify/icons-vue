<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v38m63w9l"/><path class="i96fs77gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-breed-persian" /></template>
<style>
.i96fs77gs {
  d: path("M10 16q2 1.5 4 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v38m63w9l {
  d: path("M3.5 13c0-3 1-5 2-6V3l4 2.25c1.5-.35 3.5-.35 5 0l4-2.25v4c1 1 2 3 2 6a2.5 2.5 0 0 1-1.75 4.25a2.5 2.5 0 0 1-3 2.75A2.5 2.5 0 0 1 12 21a2.5 2.5 0 0 1-3.75-1a2.5 2.5 0 0 1-3-2.75A2.5 2.5 0 0 1 3.5 13ZM9 12h.01M15 12h.01");
}

</style>
