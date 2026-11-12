<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGyu90jhRQ"><g class="k2u665ban"><circle class="b4dyhhbeb"/><path class="r4hao6bte"/></g></mask></defs><path mask="url(#SVGyu90jhRQ)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-zoom-out-line-duotone" /></template>
<style>
.b4dyhhbeb {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  stroke: var(--svg-color--gray, gray);
}

.k2u665ban {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4hao6bte {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M18.5 18.5L22 22M9 11.5h5");
}

.w49j0rbvv {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
