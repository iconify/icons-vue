<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x5sypd3oh"/><path class="po76i0m5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:join-cross" /></template>
<style>
.po76i0m5v {
  fill: currentColor;
  d: path("M2 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm16.5-15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5sypd3oh {
  d: path("M5.75 4.5h12.5m-12.5 15h12.5m-12.5-14l12.5 13m-12.5 0l12.5-13");
}

</style>
