<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mtpa6suzj"/><path class="tg2ucac5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backdoor-sharp" /></template>
<style>
.mtpa6suzj {
  d: path("M2.75 3.75h18.5v17.5H2.75zm0 4.75h18.5m-18.5 4.75H6.5m11 0h3.75M9 3.75V8.5m6-4.75V8.5");
}

.tg2ucac5t {
  d: path("M8.75 21.25v-5a3.25 3.25 0 0 1 6.5 0v5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
