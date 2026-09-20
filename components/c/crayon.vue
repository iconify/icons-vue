<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rrkj-tdzh"/><path class="zypprjoba"/><path class="eoog1sfpx"/><path class="e36-7txcz"/><path class="txef_wb1g"/><path class="h_6qtlb0b"/><path class="o9acsisvc"/><path class="aziz3obbd"/><path class="a8x06_6dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:crayon" /></template>
<style>
.a8x06_6dz {
  fill: none;
  d: path("M97 78.69v-.19");
}

.aziz3obbd {
  fill: var(--svg-color--424242, #424242);
  d: path("m52.57 100.71l5.73-5.73C46.26 85.05 33.25 69.4 33.25 69.4l-5.76 5.76c3.94 5.66 13.51 15.76 25.08 25.55M89.75 12.9l-5.76 5.76c12.94 8.79 21.51 19.26 25.63 25l5.74-5.74c-4.58-6.24-13.07-16.24-25.61-25.02");
}

.e36-7txcz {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M19.7 82.94c-1.55 1.55-.9 5.82.65 7.38l17.27 17.94c1.55 1.55 5.84 1.55 7.4 0l76.21-76.21L95.91 6.73");
}

.eoog1sfpx {
  fill: var(--svg-color--ad1414, #ad1414);
  d: path("m21.21 87.9l-3.56 5.91s3.18-1.79 7.78 4.94c3.58 5.23 3.78 14.47 3.78 14.47l10.56-6.23c-.13-.43-18.56-19.09-18.56-19.09");
}

.h_6qtlb0b {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M93.86 8.78s5.6 2.21 13.64 9.78c9.35 8.79 11.67 15.54 11.67 15.54l4.25-4.25c.78-.78 2.06-8.42-7.42-17.9S98.88 3.76 98.1 4.53");
}

.o9acsisvc {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M110.22 11.33c.32.56.58 1.19.57 1.84s-.35 1.32-.94 1.58c-.96.41-1.97-.35-2.83-.94c-1.81-1.24-4.79-2.97-6.71-4.03c-2.42-1.35-.63-4.79 2.02-4.18c2.97.68 6.4 3.1 7.89 5.73");
}

.rrkj-tdzh {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M33.37 74.96L22.16 86.18L4.32 116.43c-.5.9-.59 2.66 2.13 5.38s4.18 2.34 5.09 1.84l30.25-17.84L53 94.59z");
}

.txef_wb1g {
  fill: var(--svg-color--ef5350, #ef5350);
  d: path("M21.78 80.86s3.46 4.7 11.41 12.62c10.31 10.27 13.91 12.7 13.91 12.7l74.13-74.13L95.91 6.73");
}

.zypprjoba {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M18.47 106.52c-.17.23-9.28 10.85-9.8 11.31c-.96.86-2.25.11-1.54-1.54c.53-1.23 3.2-5.91 5.17-9.18c1.15-1.91 3.77-6.59 6.35-5.29c2.2 1.12.82 3.38-.18 4.7");
}

</style>
