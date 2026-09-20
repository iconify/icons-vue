<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bh15o6b4k"/><path class="rkqdj2nnc"/><path class="kjbh4ok5f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dps-background" /></template>
<style>
.bh15o6b4k {
  fill: var(--svg-color--d400a6, #d400a6);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kjbh4ok5f {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.97 12.004a6.158 6.158 0 0 1-10.65 4.218l.028.008c.952.074 4.702-.43 6.77-3.483c-.821.455-2.938 1.366-4.813 1.366c-1.674 0-2.745-.386-3.549-.923A6.158 6.158 0 0 1 16.308 7.8a.3.3 0 0 0-.078-.021c-.944-.074-4.677.43-6.736 3.483c.82-.456 2.925-1.366 4.787-1.366c1.703 0 2.77.402 3.578.951c.074.374.11.764.11 1.157");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rkqdj2nnc {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 14.195c0-.747.833-2.047 1.247-2.601c-.131.291-.398.84-.398 1.374c0 2.314 4.082 2.088 6.125 1.682c-.685.349-2.478 1.046-4.156 1.046C4.726 15.696 4 15.13 4 14.195m16-4.382c0 .747-.882 2.047-1.321 2.601c.14-.291.423-.84.423-1.374c0-2.314-4.325-2.088-6.487-1.682c.726-.349 2.626-1.046 4.402-1.046c2.216 0 2.983.566 2.983 1.501");
}

</style>
