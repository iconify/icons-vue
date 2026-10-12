<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="xyjv5jbvz"/><path class="abvagh55i"/><path class="o83iu1bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electrical-panel" /></template>
<style>
.abvagh55i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.25 4.75l-3 3.25h3.5l-3 3.25m-3 2.5h6m-6 2.5h6m-6 2.5h6");
}

.o83iu1bma {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 13.75h.01m-.01 2.5h.01m-.01 2.5h.01");
}

.xyjv5jbvz {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
