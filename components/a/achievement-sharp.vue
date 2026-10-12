<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y49-dkzbr"/><circle class="t-earhali"/><path class="qh9lh3bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:achievement-sharp" /></template>
<style>
.qh9lh3bgz {
  d: path("m12.13 12.57l.53 1.26l.13.33l.35.03l1.36.1l.35.03l-.26.23l-1.04.89l-.27.23l.09.34l.31 1.33l.08.34l-.3-.19l-1.16-.71l-.3-.18l-.3.18l-1.16.71l-.3.19l.08-.34l.31-1.33l.09-.34l-.27-.23l-1.04-.89l-.26-.23l.35-.03l1.36-.1l.35-.03l.13-.33l.53-1.26l.13-.32z");
}

.t-earhali {
  cx: 12px;
  cy: 15px;
  r: 6px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y49-dkzbr {
  d: path("m7.85 10.05l-2.2-6.82l-.15-.48h3.25l.13.48l1.49 5.48l.13.48l-.44.24l-1.62.86l-.44.24zm8.3 0l2.2-6.82l.15-.48h-3.25l-.13.48l-1.49 5.48l-.13.48l.44.24l1.62.86l.44.24z");
}

</style>
