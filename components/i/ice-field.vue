<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzif3dbwi"/><path class="r75k8nyui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-field" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzif3dbwi {
  d: path("m4.63 17.146l2.423-3.5A1.5 1.5 0 0 1 8.286 13h9.851a1.5 1.5 0 0 1 1.233 2.354l-2.423 3.5a1.5 1.5 0 0 1-1.233.646H5.863a1.5 1.5 0 0 1-1.233-2.354");
}

.r75k8nyui {
  d: path("m9 19.5l2-2.75l-1-1.25l2.25-2.5M15 3.75q0 2.75 2.75 2.75Q15 6.5 15 9.25q0-2.75-2.75-2.75Q15 6.5 15 3.75M6.5 7.5h.01");
}

</style>
