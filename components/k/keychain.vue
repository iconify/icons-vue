<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sh8yaiv_h"/><path class="h7ysk0jyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keychain" /></template>
<style>
.h7ysk0jyg {
  d: path("M9.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 14v7.5m0-3.75h2.5m-2.5 3h2.5");
}

.sh8yaiv_h {
  d: path("M8.75 5.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
