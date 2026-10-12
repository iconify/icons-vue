<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k6wo9cced"/><path class="ksddhx9ca"/><path class="ufgjohb2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bot-settings-sharp" /></template>
<style>
.k6wo9cced {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5H14.5v9.75H2.75z");
}

.ksddhx9ca {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 9.4h.01m4.24 0h.01");
}

.ufgjohb2j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.6 4.5V2.75m10.15 10.5L15 18h3.25l-.75 3.25l3.75-4.75H18.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
