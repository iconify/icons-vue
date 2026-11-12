<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="scpq33bsm"/><path class="q70sseccx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layer-arrow-up-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q70sseccx {
  stroke-linejoin: round;
  d: path("M12 16V4M15 7L12 4L9 7");
}

.scpq33bsm {
  d: path("M7.7873 13.1915L4.9788 14.3149L4.97783 14.3153C2.99258 15.1095 2 15.5065 2 16C2 16.4935 2.9929 16.8907 4.9788 17.6851L7.7873 18.8085L7.78814 18.8089C9.77348 19.6029 10.7663 20 12 20C13.2337 20 14.2265 19.6029 16.2119 18.8089L16.2127 18.8085L19.0212 17.6851C21.0071 16.8907 22 16.4935 22 16C22 15.5065 21.0074 15.1095 19.0222 14.3153L19.0212 14.3149L16.2127 13.1915");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
