<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xwrpq00dl"/><path class="wgt33soab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ice-cream-cone-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wgt33soab {
  d: path("M5.25 8.85217C5.25 5.12427 8.2721 2.10217 12 2.10217C15.7279 2.10217 18.75 5.12427 18.75 8.85217C18.75 10.3022 18.1 11.1022 17 11.1022H7C5.9 11.1022 5.25 10.3022 5.25 8.85217Z");
}

.xwrpq00dl {
  d: path("M7.25 11.1022L11.4143 20.9213C11.6903 21.5721 11.8285 21.8978 12 21.8978C12.1715 21.8978 12.3096 21.5722 12.5856 20.9214L15.732 13.5024M15.732 13.5024L16.75 11.1022M15.732 13.5024L9.20117 15.7022M15.732 13.5024L15.7324 13.5023");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
