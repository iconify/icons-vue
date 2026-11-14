<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsdyo3wgt"/><path class="jr7z_3bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-interest-rate-badge" /></template>
<style>
.bsdyo3wgt {
  d: path("m12.776 3.102l.279.216a1.5 1.5 0 0 0 1.123.301l.348-.048a1.27 1.27 0 0 1 1.345.777l.133.326a1.5 1.5 0 0 0 .822.822l.326.133a1.27 1.27 0 0 1 .777 1.345l-.048.348a1.5 1.5 0 0 0 .301 1.123l.216.279a1.27 1.27 0 0 1 0 1.552l-.216.279a1.5 1.5 0 0 0-.301 1.123l.048.348a1.27 1.27 0 0 1-.777 1.345l-.326.133a1.5 1.5 0 0 0-.822.822l-.133.326a1.27 1.27 0 0 1-1.345.777l-.348-.048a1.5 1.5 0 0 0-1.123.301l-.279.216a1.27 1.27 0 0 1-1.552 0l-.279-.216a1.5 1.5 0 0 0-1.123-.301l-.348.048a1.27 1.27 0 0 1-1.345-.777l-.133-.326a1.5 1.5 0 0 0-.822-.822l-.326-.133a1.27 1.27 0 0 1-.777-1.345l.048-.348a1.5 1.5 0 0 0-.301-1.123l-.216-.279a1.27 1.27 0 0 1 0-1.552l.216-.279a1.5 1.5 0 0 0 .301-1.123l-.048-.348a1.27 1.27 0 0 1 .777-1.345l.326-.133a1.5 1.5 0 0 0 .822-.822l.133-.326a1.27 1.27 0 0 1 1.345-.777l.348.048a1.5 1.5 0 0 0 1.123-.301l.279-.216a1.27 1.27 0 0 1 1.552 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jr7z_3bnu {
  d: path("M8.5 15L7 21.5L9.5 20m6-5l1.5 6.5l-2.5-1.5m-5-8l5-5m-4.75.5h.01m4.49 4h.01");
}

</style>
