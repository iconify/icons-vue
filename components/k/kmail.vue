<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p9yu8ub0v"/><path class="l19cgcpdw"/><path class="xqq-ugzzw"/><path class="m1o6uy0so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kmail" /></template>
<style>
.l19cgcpdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.58 38.725l2.828.84c.953.268 1.703-.227 1.703-.892V22.482c0-.619-.31-.992-.754-1.252l-19.24-5.635c-.78 0-1.378.525-1.378 1.314l.004 2.408");
}

.m1o6uy0so {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.972 18.958l7.465 14.615c.367.604 1.23 1.24 2.071.581l10.725-9.273M35.99 5.5v9.82v-1.535l5.5-5.499l-2.356 2.355l2.629 4.721");
}

.p9yu8ub0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.1 36.096l2.177.62c.953.268 1.703-.228 1.703-.892V19.632c0-.618-.31-.991-.754-1.251l-19.24-5.636c-.78 0-1.378.526-1.378 1.315l.004 2.26");
}

.xqq-ugzzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.246 19.8l.029 15.665c0 .697.257 1.083.81 1.294l18.82 5.667c.954.268 1.704-.227 1.704-.892V25.342c0-.618-.31-.991-.754-1.25l-19.24-5.636c-.78 0-1.378.525-1.378 1.314z");
}

</style>
