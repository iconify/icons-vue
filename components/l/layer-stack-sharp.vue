<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uoil4wvmb"/><path class="iky650bpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layer-stack-sharp" /></template>
<style>
.iky650bpj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9.5h.01m-.01 5h.01M12 7h.01M12 12h.01M12 17h.01M19 9.5h.01m-.01 5h.01");
}

.uoil4wvmb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h4.5v11.5h-4.5zm7-3.5h4.5v18.5h-4.5zm7 3.5h4.5v11.5h-4.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
