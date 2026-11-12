<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jk67y2bqf"/><path class="z5swo304v"/><path class="vocv1b5bv"/><path class="xqxrq7bcn"/><path class="f74vm3b-y"/><path class="i84zssbem"/><path class="r7t8s7bxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dna-line-duotone" /></template>
<style>
.f74vm3b-y {
  d: path("M19.7783 10.8906L16.2783 7.39062");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i84zssbem {
  d: path("M9.30469 18.1914L10.8917 19.7784");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk67y2bqf {
  d: path("M11.8476 12.1524L12.0462 12.2208C15.3052 13.3428 19.2301 12.2699 22 9.5M11.8476 12.1524L11.2902 11.9606C8.24848 10.9134 4.58525 11.9147 2 14.5M11.8476 12.1524L11.7792 11.9538C10.6572 8.69481 11.7301 4.76991 14.5 2M11.8476 12.1524L12.0394 12.7098C13.0866 15.7515 12.0853 19.4147 9.5 22");
}

.r7t8s7bxd {
  d: path("M14.5869 5.58691L12.9999 3.99989");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vocv1b5bv {
  d: path("M11.8438 6.76465L16.9222 11.8431");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xqxrq7bcn {
  d: path("M4 13.0002L7.5 16.5002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z5swo304v {
  d: path("M6.76465 11.8433L11.8431 16.9217");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
