<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="kau21vl4m"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:locate-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.kau21vl4m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 18.9291C7.9283 18.4846 5.5154 16.0717 5.0709 13L2 13C1.4477 13 1 12.5523 1 12C1 11.4477 1.4477 11 2 11L5.0709 11C5.2857 9.5038 5.9803 8.1178 7.0503 7.0503L16.9498 16.9498C15.8822 18.0197 14.4962 18.7143 13 18.9291L13 22C13 22.5523 12.5523 23 12 23C11.4477 23 11 22.5523 11 22L11 18.9291ZM13 5.0709C16.0717 5.5154 18.4846 7.9283 18.9291 11L22 11C22.5523 11 23 11.4477 23 12C23 12.5523 22.5523 13 22 13L18.7098 13C18.5243 13.2002 18.2638 13.314 17.9909 13.314C17.731 13.314 17.4817 13.2108 17.2979 13.027L17.2838 13.0411L10.9589 6.7162L10.973 6.7021C10.7892 6.5183 10.686 6.269 10.686 6.0091C10.686 5.7362 10.7998 5.4757 11 5.2902L11 2C11 1.4477 11.4477 1 12 1C12.5523 1 13 1.4477 13 2L13 5.0709Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
