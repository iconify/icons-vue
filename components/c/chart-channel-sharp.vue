<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><path class="srusw0bcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-channel-sharp" /></template>
<style>
.srusw0bcw {
  d: path("m7.75 15.25l3.5-4.5l3 2.5l5-6");
}

.vf_31rbpy {
  d: path("M3.75 3.75v16.5h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
