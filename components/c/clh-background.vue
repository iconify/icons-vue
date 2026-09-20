<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="exjzufb1b"/><path class="z3vh4nbly"/><path class="bhg1hwy-y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clh-background" /></template>
<style>
.bhg1hwy-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 4.258a.28.28 0 0 0-.279.279v2.539a.28.28 0 0 0 .279.279h3.334v3.334a.28.28 0 0 0 .175.258a.2.2 0 0 0 .103.02h2.54A.284.284 0 0 0 20 10.69V4.26z");
}

.exjzufb1b {
  fill: var(--svg-color--0e1d51, #0e1d51);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z3vh4nbly {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.422 19.726a8.2 8.2 0 0 1-5.326-2.519a7.58 7.58 0 0 1-2.095-5.336a7.6 7.6 0 0 1 2.276-5.264c1.43-1.415 3.628-2.256 5.677-2.349a.29.29 0 0 1 .304.289v2.53a.28.28 0 0 1-.082.19a.3.3 0 0 1-.202.088c-.944.052-2.116.31-2.88.846A4.66 4.66 0 0 0 7.098 12c0 2.611 2.323 4.665 4.903 4.645c2.467-.021 4.748-1.879 4.903-4.372a.27.27 0 0 1 .088-.19a.3.3 0 0 1 .206-.083h2.498a.31.31 0 0 1 .282.182a.3.3 0 0 1 .023.112a7.6 7.6 0 0 1-.749 2.993a7.8 7.8 0 0 1-1.899 2.467a8.1 8.1 0 0 1-2.756 1.564a8.5 8.5 0 0 1-3.174.408");
}

</style>
