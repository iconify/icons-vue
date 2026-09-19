<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xxya5lbpq"/><path class="o_0z8p78q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anker-app" /></template>
<style>
.o_0z8p78q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.167 32.5L22 42.5l.425-8h-3.591L26 24.5l-.425 8z");
}

.xxya5lbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 37.555L27.578 7.711a4 4 0 0 0-7.156 0L5.5 37.555h6.473L24 13.5l12.027 24.055z");
}

</style>
