<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vgx27qokn"/><path class="o8scmcc3i"/><path class="vsmfi0bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:login-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8scmcc3i {
  d: path("M3 12h10");
}

.vgx27qokn {
  d: path("M15 3h6v18h-6");
}

.vsmfi0bcq {
  d: path("m10 9 3 3 -3 3");
}

</style>
