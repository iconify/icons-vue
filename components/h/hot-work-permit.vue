<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfwxxkb2w"/><path class="wue-a4bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-work-permit" /></template>
<style>
.dfwxxkb2w {
  d: path("M13.171 21.5H4v-19h9l5 5v2.429");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wue-a4bfd {
  d: path("M13 2.5v5h5M7.5 11h7m-7 4H11m7.25-2.25c.5 1.75 3.25 3 3.25 5.5a3.25 3.25 0 0 1-6.5 0c0-1.25.75-2.25 1.5-2.75q0 1.125.75 1.5c0-1.5.25-3 1-4.25");
}

</style>
