<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a81qvikhv"/><path class="q_nfnc6mi"/><path class="ekpyzob7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:banner-sharp" /></template>
<style>
.a81qvikhv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5h18.5v11H2.75zM7 9.5v3");
}

.ekpyzob7n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12h7.25");
}

.q_nfnc6mi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
