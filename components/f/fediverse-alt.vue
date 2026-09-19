<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ya52ymbbe"/><circle class="eie6d9w6e"/><circle class="fa999tbuq"/><circle class="v9n6mevfa"/><circle class="h0lpvwbyf"/><path class="ft8mxbcox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fediverse-alt" /></template>
<style>
.eie6d9w6e {
  cx: 41.284px;
  cy: 22.033px;
  r: 4.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fa999tbuq {
  cx: 31.428px;
  cy: 41.289px;
  r: 4.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ft8mxbcox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.107 10.468l-12.02 23.706m25.455-10.208L13.919 36.172m16.857.958l-4.113-26.258M9.689 19.48l18.766 18.826m8.67-16.939l-26.282-4.028m11.347-8.69l-11.719 5.944m-1.095 19.12L7.359 20.66m19.857 20.013l-13.037-1.907m25.186-12.984L33.346 37.54M28.984 9.694l9.327 9.357");
}

.h0lpvwbyf {
  cx: 6.716px;
  cy: 16.497px;
  r: 4.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v9n6mevfa {
  cx: 10.064px;
  cy: 37.867px;
  r: 4.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ya52ymbbe {
  cx: 26.011px;
  cy: 6.711px;
  r: 4.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
