<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pemn838wn"/><path class="e10tuqb4v"/><path class="xg3pq9szd"/><path class="csu0owb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:doctor-outline-thin" /></template>
<style>
.csu0owb4a {
  d: path("M9.5 17h5");
}

.e10tuqb4v {
  d: path("M5.4 15a6.6 6.6 0 0 1 13.2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xg3pq9szd {
  d: path("M12 14.5v5");
}

</style>
