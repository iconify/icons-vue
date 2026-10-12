<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f2zhoqb2c"/><path class="bn1ubexrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-cloud-sharp" /></template>
<style>
.bn1ubexrk {
  d: path("M9.75 16.5h4.75a1.75 1.75 0 0 0 .25-3.48a2.75 2.75 0 0 0-5.3-.5a2 2 0 0 0 .3 3.98Z");
}

.f2zhoqb2c {
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v11.45H2.75v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
