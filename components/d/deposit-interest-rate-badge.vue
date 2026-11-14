<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mplv8xbza"/><path class="jr7z_3bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-interest-rate-badge" /></template>
<style>
.jr7z_3bnu {
  d: path("M8.5 15L7 21.5L9.5 20m6-5l1.5 6.5l-2.5-1.5m-5-8l5-5m-4.75.5h.01m4.49 4h.01");
}

.mplv8xbza {
  d: path("m12 2.5l1.553 1.204l1.947-.266l.743 1.819L18.062 6l-.266 1.947L19 9.5l-1.204 1.553l.266 1.947l-1.819.743l-.743 1.819l-1.947-.266L12 16.5l-1.553-1.204l-1.947.266l-.743-1.819L5.938 13l.266-1.947L5 9.5l1.204-1.553L5.938 6l1.819-.743l.743-1.819l1.947.266Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
