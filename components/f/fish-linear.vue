<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yghwcjb0i"/><path class="rmgl_cimk"/><path class="f_pnezpvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fish-linear" /></template>
<style>
.f_pnezpvd {
  d: path("M6.76367 10.5H6.76377");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmgl_cimk {
  d: path("M10.4629 8.19995C11.7629 10.6 11.7629 13.4 10.4629 15.8");
}

.yghwcjb0i {
  d: path("M2.47656 12C2.47656 8.2 6.17656 5.5 10.5766 5.5C13.7766 5.5 15.1766 8.6 16.4766 10.4C17.1766 11.3 19.5766 6.6 20.9766 7.1C22.0766 7.5 21.3766 9.6 20.1766 11.2C19.6766 11.8 19.6766 12.2 20.1766 12.8C21.3766 14.4 22.0766 16.5 20.9766 16.9C19.5766 17.4 17.1766 12.7 16.4766 13.6C15.1766 15.4 13.7766 18.5 10.5766 18.5C6.17656 18.5 2.47656 15.8 2.47656 12Z");
}

</style>
