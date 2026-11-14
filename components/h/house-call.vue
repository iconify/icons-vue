<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5rcuob1t"/><path class="trn1rwa5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-call" /></template>
<style>
.s5rcuob1t {
  d: path("M10.9 18.5H2.5V7h15v4.2M7.25 7V5C7.25 4 8 3.5 9 3.5h2c1 0 1.75.5 1.75 1.5v2M10 10v5.5m-2.75-2.75h5.5m1.5 5.25L18 14.5l3.75 3.5");
}

.trn1rwa5g {
  d: path("M15.5 17v4.5h5V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
