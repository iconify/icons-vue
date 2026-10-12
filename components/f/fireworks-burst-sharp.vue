<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ak0c6fe9j"/><path class="h4s8impbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fireworks-burst-sharp" /></template>
<style>
.ak0c6fe9j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 12h3.75m-4.56 1.94l2.66 2.66M12 14.75v3.75m-1.94-4.56L7.4 16.6M9.25 12H5.5m4.56-1.94L7.4 7.4M12 9.25V5.5m1.94 4.56L16.6 7.4");
}

.h4s8impbv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.75 12h.01m-2.57 6.19h.01M12 20.75h.01m-6.2-2.56h.01M3.25 12h.01m2.55-6.19h.01M12 3.25h.01m6.18 2.56h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
