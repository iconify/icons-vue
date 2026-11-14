<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhkuqgz9x"/><path class="eooy75brd"/><path class="hxyabovjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:double-espresso" /></template>
<style>
.eooy75brd {
  d: path("M8.75 9H9a1.5 1.5 0 0 1 0 3h-.75m5-4.5h5.5v3a2.75 2.75 0 0 1-5.5 0Z");
}

.hxyabovjh {
  d: path("M18.75 9H19a1.5 1.5 0 0 1 0 3h-.75m-15.5 4h18.5");
}

.mhkuqgz9x {
  d: path("M3.25 7.5h5.5v3a2.75 2.75 0 0 1-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
