<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m5b33_bpj"/><path class="a6jo9qb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-add-angle-line-duotone" /></template>
<style>
.a6jo9qb1m {
  d: path("M15 13L12 13M12 13L9 13M12 13L12 10M12 13L12 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5b33_bpj {
  d: path("M7.71175 3.86711L6.32691 4.69205C4.02619 6.06258 2.87583 6.74785 2.33537 7.87519C1.79491 9.00253 1.98463 10.3211 2.36407 12.9581L2.64284 14.8955C3.13025 18.2829 3.37396 19.9766 4.54903 20.9884C5.72409 22.0002 7.44737 22.0002 10.8939 22.0002H13.1061C16.5526 22.0002 18.2759 22.0002 19.451 20.9884C20.626 19.9766 20.8697 18.2829 21.3572 14.8955L21.6359 12.9581C22.0154 10.3211 22.2051 9.00253 21.6646 7.87519C21.1242 6.74785 19.9738 6.06258 17.6731 4.69205L16.2882 3.86711C14.199 2.62253 13.1543 2.00024 12 2.00024C10.8457 2.00024 9.80104 2.62253 7.71175 3.86711Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
