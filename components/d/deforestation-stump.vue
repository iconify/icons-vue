<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hde3qetzm"/><path class="dzo-c2hxo"/><path class="he77yqknm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deforestation-stump" /></template>
<style>
.dzo-c2hxo {
  d: path("M5 7.5v10q0 1.5-1.5 3h17Q19 19 19 17.5v-10");
}

.hde3qetzm {
  d: path("M5 7.5a7 3.5 0 1 0 14 0a7 3.5 0 1 0-14 0Z");
}

.he77yqknm {
  d: path("M9 7.5a3 1 0 1 0 6 0a3 1 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
