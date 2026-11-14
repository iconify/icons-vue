<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mgk_s2frb"/><path class="yskg-rb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antibody-test" /></template>
<style>
.mgk_s2frb {
  d: path("M7 2.5v14c0 2.75 2.25 5 5 5s5-2.25 5-5v-14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yskg-rb0r {
  d: path("M12 17.5V13L9.75 9.5M12 13l2.25-3.5");
}

</style>
