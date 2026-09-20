<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oep2ilbfs"/><path class="gna4ml3bq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:card-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gna4ml3bq {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.25 17.878l3.28-1.643l-11.765-5.873L4.48 12l11.765 5.878zM12 20l3.294-1.642l-7.53-3.765l-3.27 1.642zm7.52-8l-3.285 1.638L12.96 12l3.28-1.638zM8.71 5.647L12.006 4l3.289 1.647L12 7.285L8.71 5.642zm-.96.475L4.47 7.765l7.53 3.76l3.28-1.638l-7.53-3.76zm8.485 3.29l3.29-1.647l-3.28-1.633l-3.294 1.642z");
}

.oep2ilbfs {
  fill: var(--svg-color--37eb77, #37eb77);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
