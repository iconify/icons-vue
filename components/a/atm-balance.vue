<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuknfnbhx"/><path class="yurvdubsq"/><path class="pn8692y0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-balance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kuknfnbhx {
  d: path("M8.375 2.5h7.25A4.375 4.375 0 0 1 20 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 17.125V6.875A4.375 4.375 0 0 1 8.375 2.5");
}

.pn8692y0e {
  d: path("M11 6.5c0-.3-.43-.5-1-.5c-.7 0-1.12.35-1 1c-.12.92 2.12.47 2 2c.12.38-.35.75-1 .75c-.6 0-1.03-.25-1-.75m1-3.75V6m0 3.75v.75M12.5 8h2m-8 6.25h11M7 17.75h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01");
}

.yurvdubsq {
  d: path("M8.75 4.25h6.5A1.75 1.75 0 0 1 17 6v3.75a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 9.75V6a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
