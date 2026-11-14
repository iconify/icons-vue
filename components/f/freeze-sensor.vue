<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr96ky69n"/><path class="fp41zld_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freeze-sensor" /></template>
<style>
.fp41zld_e {
  d: path("M10.25 5.75L12 7.5l1.75-1.75m2.788 1.609l-.641 2.391l2.391.641m0 3.218l-2.391.641l.641 2.391M13.75 18.25L12 16.5l-1.75 1.75m-2.788-1.609l.641-2.391l-2.391-.641m0-3.218l2.391-.641l-.641-2.391");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rr96ky69n {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 5.5v13m5.629-9.75l-11.258 6.5m11.258 0L6.371 8.75");
}

</style>
