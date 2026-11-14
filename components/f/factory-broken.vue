<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czeiw6b4w"/><path class="lgsv-dsoe"/><path class="kas2a1byc"/><path class="bjzp-eh6w"/><path class="m-t34-03n"/><path class="kyakhi5ku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:factory-broken" /></template>
<style>
.bjzp-eh6w {
  d: path("M7 17.5H8.5");
}

.czeiw6b4w {
  d: path("M22 22H2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kas2a1byc {
  d: path("M3 12.19V4.2C3 3.1629 3 2.6444 3.3222 2.3222C3.6444 2 4.1629 2 5.2 2H5.8C6.8371 2 7.3556 2 7.6778 2.3222C8 2.6444 8 3.1629 8 4.2V11.7C8 12.0771 8 12.2657 8.0949 12.3142C8.1899 12.3627 8.3427 12.2522 8.6483 12.0312L12.8793 8.9719L12.8801 8.97133C13.6436 8.41931 14.0254 8.14324 14.2626 8.2645C14.5 8.3858 14.5 8.8572 14.5 9.8V11.7C14.5 12.0771 14.5 12.2657 14.5949 12.3142C14.6899 12.3627 14.8427 12.2522 15.1483 12.0312L15.1483 12.0312L19.3793 8.9719L19.3801 8.97133C20.1436 8.41931 20.5254 8.14324 20.7626 8.2645C21 8.3858 21 8.8572 21 9.8V22");
}

.kyakhi5ku {
  d: path("M15.5 17.5H17");
}

.lgsv-dsoe {
  d: path("M3 22V15.79");
}

.m-t34-03n {
  d: path("M11.25 17.5H12.75");
}

</style>
