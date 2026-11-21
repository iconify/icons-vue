<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gqyt8bbgj"/><path class="a1rutgvke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boxing-glove-line-duotone" /></template>
<style>
.a1rutgvke {
  d: path("M6.5957 16.5H16.9957M10.2957 19H13.2957");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gqyt8bbgj {
  d: path("M5.56461 8.7363C5.59431 4.6 8.29431 2.5 12.5943 2.5C17.1943 2.5 19.9943 5.3 19.9943 10C19.9943 13.3 18.5943 15.5 16.9943 16.5V19.5C16.9943 20.8 16.0943 21.5 14.7943 21.5H8.79431C7.49431 21.5 6.59431 20.8 6.59431 19.5V16.5L5.19431 14.5C3.69431 12.4 3.59431 10.2 4.99431 9.1C6.19431 8.1 7.89431 8.4 8.99431 9.6L9.79431 10.5C10.5943 11.4 10.3943 12.8 9.39431 13.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
