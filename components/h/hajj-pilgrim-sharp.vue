<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g828vzbqg"/><path class="p5fhu3n4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hajj-pilgrim-sharp" /></template>
<style>
.g828vzbqg {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

.p5fhu3n4j {
  d: path("m7.25 21.25l1-8.25a3.75 3.75 0 0 1 7.5 0l1 8.25Zm1.75-10L15.75 17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
