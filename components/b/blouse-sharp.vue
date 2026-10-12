<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a_3e9tbwf"/><path class="dr06qo-kp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blouse-sharp" /></template>
<style>
.a_3e9tbwf {
  d: path("M9.25 3.5h6.5l.87.49l2.76 1.52l.87.49l.15.99l.7 4.52l.15.99l-.97.24l-1.06.27l-.97.24l-.26-.96l-.23-.83l-.032-.117l-.24.04l.032.117l.21 8.25l.02 1H6.25l.02-1l.21-8.25l.002-.122l-.24-.04l-.002.122l-.23.83l-.26.96l-.97-.24l-1.06-.27l-.97-.24l.15-.99l.7-4.52l.15-.99l.87-.49l2.76-1.52l.87-.49z");
}

.dr06qo-kp {
  d: path("M11.48 7.2L9.52 6.05L9 5.75v3.5l.52-.3l1.96-1.15l.52-.3zm1.04 0l1.96-1.15l.52-.3v3.5l-.52-.3l-1.96-1.15l-.52-.3zm-1.27 1.3l-1 3.5m2.5-3.5l1 3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
