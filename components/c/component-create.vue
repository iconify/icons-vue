<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b9qwi0o7t"/><path class="zfgzjccvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-create" /></template>
<style>
.b9qwi0o7t {
  d: path("M12.183 19.834L11 20.5L3 16V7l8-4.5L19 7v5.221");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfgzjccvr {
  d: path("m3 7l8 4.5L19 7m-8 4.5v9m7-5.5v6m-3-3h6");
}

</style>
