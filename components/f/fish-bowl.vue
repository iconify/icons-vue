<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_26ab3xk"/><path class="p50mw8sun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-bowl" /></template>
<style>
.p50mw8sun {
  d: path("M8 12c1.5-2.5 4.5-2.5 6 0l2.25-1.75v3.5L14 12c-1.5 2.5-4.5 2.5-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_26ab3xk {
  d: path("M8 4.25a8.25 8.25 0 0 0-.25 14.25h8.5A8.25 8.25 0 0 0 16 4.25m-9 0h10M6 21.5h12");
}

</style>
