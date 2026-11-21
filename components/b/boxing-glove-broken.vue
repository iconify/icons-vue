<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rscb09bbp"/><path class="j3gb0j5bn"/><path class="j7-t56hjo"/><path class="bxci71b5h"/><path class="xc66usbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boxing-glove-broken" /></template>
<style>
.bxci71b5h {
  d: path("M6.5957 16.5H16.9957V19.5C16.9957 20.8 16.0957 21.5 14.7957 21.5H8.7957C7.4957 21.5 6.5957 20.8 6.5957 19.5V16.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3gb0j5bn {
  d: path("M19.362 6.5246C19.7774 7.5216 19.9961 8.6866 19.9961 10C19.9961 13.3 18.5961 15.5 16.9961 16.5");
}

.j7-t56hjo {
  d: path("M6.59431 16.5L5.19431 14.5C3.69431 12.4 3.59431 10.2 4.99431 9.1C6.19431 8.1 7.89431 8.4 8.99431 9.6L9.79431 10.5C10.5943 11.4 10.3943 12.8 9.39431 13.4");
}

.rscb09bbp {
  d: path("M5.56641 8.7363C5.59611 4.6 8.29611 2.5 12.5961 2.5C14.4967 2.5 16.09 2.978 17.3055 3.8705");
}

.xc66usbha {
  d: path("M10.2949 19H13.2949");
}

</style>
