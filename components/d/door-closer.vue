<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aflf73b6a"/><path class="c_xxeqb1q"/><path class="z_6415bmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-closer" /></template>
<style>
.aflf73b6a {
  d: path("M4 21.5v-17a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v17");
}

.c_xxeqb1q {
  d: path("M7 5.5h7V9H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_6415bmg {
  d: path("m14 7.25l3.25 4.5l-6.75 1.5");
}

</style>
