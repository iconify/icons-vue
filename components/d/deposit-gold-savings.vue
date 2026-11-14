<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vrd7as-qq"/><path class="d4ftvbbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-gold-savings" /></template>
<style>
.d4ftvbbdu {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m0 12.75l1.75-4.75h5L22 21.25ZM14.75 18h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrd7as-qq {
  d: path("M11.732 18c-.61-.004-1.075-.031-1.732-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q-.001.933-.28 1.743");
}

</style>
