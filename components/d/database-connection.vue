<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwf2a6bnw"/><path class="atinadbmh"/><path class="rj2amhbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-connection" /></template>
<style>
.atinadbmh {
  d: path("M2.5 4.5v6a4.5 1.75 0 0 0 9 0v-6m1 9a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwf2a6bnw {
  d: path("M2.5 4.5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0");
}

.rj2amhbku {
  d: path("M12.5 13.5v6a4.5 1.75 0 0 0 9 0v-6M7 12.25V17h5.5");
}

</style>
