<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w54uzybrx"/><path class="fdgleknxc"/><path class="fec6d0rij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guard-dog" /></template>
<style>
.fdgleknxc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 10h.01");
}

.fec6d0rij {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 18.25h7.75");
}

.w54uzybrx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.25V14.5c-1.5-1.25-2.25-3-2.25-5l.75-6l3.25 3h3.5c1.75 0 3 .75 4 1.75l1.5 1.5h2.5a1.5 1.5 0 0 1 1.5 1.5v1a2 2 0 0 1-2 2H15.5l-1.25 1.5v5.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
