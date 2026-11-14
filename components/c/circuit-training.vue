<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r2gwdbbsx"/><path class="f092mrbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circuit-training" /></template>
<style>
.f092mrbti {
  d: path("M15.25 6H18V3.25M6.75 9.75H9.5v4.5H6.75Zm7.75 0h2.75v4.5H14.5ZM9.5 12h5");
}

.r2gwdbbsx {
  d: path("M20.25 14.25A8.5 8.5 0 1 1 18 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
