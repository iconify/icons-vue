<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yp42yebaz"/><path class="xmr5ibbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:despegar" /></template>
<style>
.xmr5ibbqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.5C15.717 42.5 24 34.217 24 24S15.717 5.5 5.5 5.5z");
}

.yp42yebaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v37H24c10.217 0 18.5-8.283 18.5-18.5S34.217 5.5 24 5.5z");
}

</style>
