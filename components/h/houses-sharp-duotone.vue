<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="by6k8zbjb"/><path clip-rule="evenodd" class="fbpfqrbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:houses-sharp-duotone" /></template>
<style>
.by6k8zbjb {
  stroke-opacity: 0.4;
  d: path("M1.6141 7.1912L2 6.8909L7 3L10.456 5.6894L10.8419 5.9897M4 5.3346L4 10.7134L4 11.7134");
}

.fbpfqrbiw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.3857 7.2108C13.7469 6.92973 14.253 6.92973 14.6142 7.2108L23 13.7362L21.7714 15.3153L21 14.7147V20.9999C20.9998 21.552 20.5522 21.9999 20 21.9999H17V17.9999C17 16.343 15.6569 14.9999 14 14.9999C12.3431 14.9999 11 16.343 11 17.9999V21.9999H7.99996C7.44779 21.9998 7.00012 21.552 6.99996 20.9999V14.7147L6.22848 15.3153L4.99996 13.7362L13.3857 7.2108Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
