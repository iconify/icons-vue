<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a1wspjb6z"/><path class="schs_svoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-emergency-cover" /></template>
<style>
.a1wspjb6z {
  d: path("m2.5 10.5l7.75-7l7.75 7v10H2.5Z");
}

.schs_svoz {
  d: path("M7.75 20.5v-5h5v5m8.25-8v5m0 3.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
