<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w926xhbop"/><path class="atw1d4nfg"/><path class="fhqd5mdep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:copyright-image" /></template>
<style>
.atw1d4nfg {
  d: path("M2.5 14L7 9.5l5.258 5.258M12.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm1.5 10a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.fhqd5mdep {
  d: path("M19 16.75a1.5 1.5 0 1 0 0 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w926xhbop {
  d: path("M11.5 17.5h-9v-14h17v8.1");
}

</style>
