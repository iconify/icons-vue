<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qmrbohblm"/><path class="dofyk9bdo"/><path class="pj2kwebju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:king-cake" /></template>
<style>
.dofyk9bdo {
  d: path("M2.5 8v7a9.5 4 0 0 0 19 0V8");
}

.pj2kwebju {
  d: path("M8.5 8a3.5 1.25 0 1 0 7 0a3.5 1.25 0 1 0-7 0Zm-3.25 2.75v2.75M12 12v3.5m6.75-4.75v2.75");
}

.qmrbohblm {
  d: path("M2.5 8a9.5 4 0 1 0 19 0a9.5 4 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
