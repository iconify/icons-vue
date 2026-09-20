<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-pcdbceg"/><path class="kafgvtbap"/><path class="peew4rbrn"/><path class="r7ao24n4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heavy-snow-outline-thin" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kafgvtbap {
  d: path("M7 15.5v5m-2.5 0 5 -5");
}

.peew4rbrn {
  d: path("M17 15.5v5m-2.5 0 5 -5");
}

.r7ao24n4h {
  d: path("M4 22h16");
}

</style>
