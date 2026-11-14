<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j568z7b2h"/><path class="fmdezkbii"/><path class="fghzufttv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:celtic-knot" /></template>
<style>
.fghzufttv {
  d: path("M3 19.75a9 9 0 0 1 18 0");
}

.fmdezkbii {
  d: path("M12 4.25a9 9 0 0 0 9 15.5");
}

.j568z7b2h {
  d: path("M12 4.25a9 9 0 0 1-9 15.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
