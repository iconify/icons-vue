<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vspug48qm"/><path class="t2b2r8brw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:days-without-accident" /></template>
<style>
.t2b2r8brw {
  d: path("m8 15l2.75 2.75L16 12.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vspug48qm {
  d: path("M3 4.5h18V21H3Zm5-2v3.75m8-3.75v3.75M3 9h18");
}

</style>
