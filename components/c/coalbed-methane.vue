<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jjidfxfsb"/><path class="p58mi_s6n"/><path class="lv4tm6bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coalbed-methane" /></template>
<style>
.jjidfxfsb {
  d: path("M2 21.5L3 16l5-3l7 .5l5 2l2 6Z");
}

.lv4tm6bjs {
  d: path("m10.5 17.5l9.5-2m-5-13c2.5 2.5 4 5 4 7a4 4 0 0 1-8 0c0-2 1-3.5 2-4.5c.5 1.5 1 2 1.5 2c-.5-2-.5-3.25.5-4.5Z");
}

.p58mi_s6n {
  fill: currentColor;
  d: path("m3 16l5-3l2.5 4.5l-1.5 4H2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
