<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uche1nbyo"/><path class="ygdf-sbwv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ceur-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uche1nbyo {
  fill: var(--svg-color--3bc77b, #3bc77b);
  d: path("M24 0H0v24h24z");
}

.ygdf-sbwv {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.745 11.997a3.22 3.22 0 0 0 2.278-.934l.47 1.574a4.764 4.764 0 0 1-7.158-2.138H9.847l.49-1h1.723a4.8 4.8 0 0 1-.05-.998h-1.598l.484-.999h1.269a4.76 4.76 0 0 1 7.312-2.647l-.5 1.538a3.237 3.237 0 0 0-5.229 1.109h4.865l-.375.999h-4.73c-.025.335 0 .672.075.999h4.47l-.374.999h-3.671a3.25 3.25 0 0 0 2.737 1.498M4.508 13.246a6.74 6.74 0 0 1 4.505-6.363a8.6 8.6 0 0 0 .2 2.077a4.745 4.745 0 1 0 6.293 6.384q.997.247 2.068.255a6.743 6.743 0 0 1-13.066-2.353");
}

</style>
