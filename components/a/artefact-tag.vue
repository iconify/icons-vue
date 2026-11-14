<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="idp69lb1m"/><path class="mj-f3ibbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artefact-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idp69lb1m {
  d: path("M4.626 10.226L7.72 6.851A2.63 2.63 0 0 1 9.655 6h8.22A2.625 2.625 0 0 1 20.5 8.625v6.75A2.625 2.625 0 0 1 17.875 18h-8.22a2.63 2.63 0 0 1-1.935-.851l-3.094-3.375a2.625 2.625 0 0 1 0-3.548");
}

.mj-f3ibbm {
  d: path("M6.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M12 10h5.5M12 14h4");
}

</style>
