<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGck3wjecJ" class="kh55oce4s"/></defs><use href="#SVGck3wjecJ" class="c-zrgpb5l"/><path class="w86_wtiak"/><use href="#SVGck3wjecJ" class="c-zrgpb5l"/><path class="j8ptry99k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aerofoil" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j8ptry99k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.9 32.2l3.28-6.56h8.2l3.28 6.56z");
}

.kh55oce4s {
  fill: none;
  stroke: currentColor;
  d: path("m10.06 15.8l9.84 16.4h14.76l6.56-9.84H28.1l-4.92-6.56z");
}

.w86_wtiak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.9 32.2l3.28-6.56h8.2l3.28 6.56zm18.04-4.92h6.56l-3.28-4.92zM6.78 24L3.5 19.08h5.248zm3.28-8.2L6.78 24h8.2z");
}

</style>
