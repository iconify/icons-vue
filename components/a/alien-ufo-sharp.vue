<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kl72mub_a"/><path class="s5_h9825b"/><path class="y740f7uyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien-ufo-sharp" /></template>
<style>
.kl72mub_a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5a9.25 3.25 0 1 0 18.5 0a9.25 3.25 0 1 0-18.5 0Z");
}

.s5_h9825b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.66c0-3.66 2-5.91 4.5-5.91s4.5 2.25 4.5 5.91q-4.5-.82-9 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y740f7uyi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 10h.01m3.49 0h.01M7.5 15.5h.01m4.49.75h.01m4.49-.75h.01");
}

</style>
