<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="six_gvzxd"/><path class="rgtjrzndh"/><path class="hn8qjl2lr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:back-soon-sign" /></template>
<style>
.hn8qjl2lr {
  d: path("M12 12.25V14l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rgtjrzndh {
  d: path("M9 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.six_gvzxd {
  d: path("M8 8h8a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 16 20H8a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 8 8m1-4.5V8m6-4.5V8");
}

</style>
