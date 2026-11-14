<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ouxdkfnjb"/><path class="en2pk-bmn"/><path class="w65n89bic"/><path class="egv269rzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exposure-bracket" /></template>
<style>
.egv269rzj {
  d: path("M4.75 16v2.5h14.5V16");
}

.en2pk-bmn {
  d: path("M9.75 5h4.5v8h-4.5ZM17 5h4.5v8H17Z");
}

.ouxdkfnjb {
  fill: currentColor;
  d: path("M2.5 5H7v8H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w65n89bic {
  fill: currentColor;
  d: path("M9.75 9.5h4.5V13h-4.5Z");
}

</style>
