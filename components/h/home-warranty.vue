<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="llpwdsf8m"/><path class="xbbzl_b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-warranty" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llpwdsf8m {
  d: path("m12.776 3.102l.279.216a1.5 1.5 0 0 0 1.123.301l.348-.048a1.27 1.27 0 0 1 1.345.777l.133.326a1.5 1.5 0 0 0 .822.822l.326.133a1.27 1.27 0 0 1 .777 1.345l-.048.348a1.5 1.5 0 0 0 .301 1.123l.216.279a1.27 1.27 0 0 1 0 1.552l-.216.279a1.5 1.5 0 0 0-.301 1.123l.048.348a1.27 1.27 0 0 1-.777 1.345l-.326.133a1.5 1.5 0 0 0-.822.822l-.133.326a1.27 1.27 0 0 1-1.345.777l-.348-.048a1.5 1.5 0 0 0-1.123.301l-.279.216a1.27 1.27 0 0 1-1.552 0l-.279-.216a1.5 1.5 0 0 0-1.123-.301l-.348.048a1.27 1.27 0 0 1-1.345-.777l-.133-.326a1.5 1.5 0 0 0-.822-.822l-.326-.133a1.27 1.27 0 0 1-.777-1.345l.048-.348a1.5 1.5 0 0 0-.301-1.123l-.216-.279a1.27 1.27 0 0 1 0-1.552l.216-.279a1.5 1.5 0 0 0 .301-1.123l-.048-.348a1.27 1.27 0 0 1 .777-1.345l.326-.133a1.5 1.5 0 0 0 .822-.822l.133-.326a1.27 1.27 0 0 1 1.345-.777l.348.048a1.5 1.5 0 0 0 1.123-.301l.279-.216a1.27 1.27 0 0 1 1.552 0M9 16l-1.5 5.5l2-1.25L11 21.5l.5-4.5m3.5-1l1.5 5.5l-2-1.25L13 21.5l-.5-4.5");
}

.xbbzl_b_s {
  d: path("m9.439 9.561l1.5-1.5a1.5 1.5 0 0 1 2.122 0l1.5 1.5a1.5 1.5 0 0 1 .439 1.06v.879a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 11.5v-.879a1.5 1.5 0 0 1 .439-1.06");
}

</style>
