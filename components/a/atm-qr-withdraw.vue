<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5vc2sbec"/><path class="qh04z_b1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-qr-withdraw" /></template>
<style>
.q5vc2sbec {
  d: path("M3 3h6v6H3Zm12 0h6v6h-6ZM3 15h6v6H3Zm3-9h.01M18 6h.01M6 18h.01M12 4h.01M12 8h.01M4 12h.01M8 12h.01M12 12h.01M16 12h.01M20 12h.01M14 15.75h8v5.5h-8Z");
}

.qh04z_b1y {
  d: path("M16.75 18.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
