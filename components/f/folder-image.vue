<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yobce9d-m"/><path class="ve84-8o-u"/><path class="totlwmxka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-image" /></template>
<style>
.totlwmxka {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 13.5h.01");
}

.ve84-8o-u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 17.25l3-3.25l2.5 2.5l1.5-1.5l2 2.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yobce9d-m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v6.45a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Zm0 3.5h18.5");
}

</style>
