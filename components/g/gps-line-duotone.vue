<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xtx0s6u8w"/><path class="zleje_bse"/><path class="hv3siab8m"/><path class="jft98ub-s"/><path class="e34edehjy"/><path class="cax_t5mes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gps-line-duotone" /></template>
<style>
.cax_t5mes {
  d: path("M12 22V20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.e34edehjy {
  d: path("M12 4V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hv3siab8m {
  d: path("M2 12L4 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jft98ub-s {
  d: path("M20 12L22 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xtx0s6u8w {
  d: path("M20 12C20 16.4183 16.4183 20 12 20C7.58172 20 4 16.4183 4 12C4 7.58172 7.58172 4 12 4C16.4183 4 20 7.58172 20 12Z");
}

.zleje_bse {
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
