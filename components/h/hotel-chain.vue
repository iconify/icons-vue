<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="buszmlzcr"/><path class="z4rkzkwtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hotel-chain" /></template>
<style>
.buszmlzcr {
  d: path("M12.3 21.5H4v-19h11.5v11.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4rkzkwtr {
  d: path("M8.25 21.5v-4h3v.9m0 .2v2.9M7 6.5h.01m5.49 0h.01M7 11h.01m5.49 0h.01m3.99 5.5H16a2 2 0 0 0 0 4h.5m3-4h.5a2 2 0 0 1 0 4h-.5m-3-2h3");
}

</style>
