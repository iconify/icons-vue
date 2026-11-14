<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_3kaccce"/><path class="v9iyn8i_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:format-painter-off" /></template>
<style>
.m_3kaccce {
  d: path("M6.9 3h9.6v6h-3.6M5.1 9H3.5V7.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9iyn8i_z {
  d: path("M16.5 6H19q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T20 7v4q0 .098-.019.195t-.057.188t-.093.173q-.054.081-.124.151t-.151.124q-.082.055-.173.093t-.188.057T19 12h-3.072M13.5 17.4V21h-3v-6.5h.1m-7.1-11l17 17");
}

</style>
