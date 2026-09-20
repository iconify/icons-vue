<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbrfvvuri"/><path class="g1jxn6bfq"/><circle class="hx12z5kwr"/><circle class="azdesn56y"/><path class="tm7aidkax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:babyphone" /></template>
<style>
.azdesn56y {
  cx: 32.094px;
  cy: 24.096px;
  r: 2.001px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g1jxn6bfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.914 22.2a6.2 6.2 0 0 1-1.935-3.511h12.196a6.47 6.47 0 0 1-2.019 3.603M30.134 23.7a8 8 0 0 1-1.101.114a6 6 0 0 1-1.135-.114");
}

.hx12z5kwr {
  cx: 25.893px;
  cy: 24.096px;
  r: 2.001px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jbrfvvuri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.717 30.278a62 62 0 0 1-6.302-1.11a3.11 3.11 0 0 0-3 .58c-.53.54-2.061 2.05-3.652 3.611A28.7 28.7 0 0 1 14.66 20.245c1.55-1.59 3.001-3.11 3.591-3.64a3.11 3.11 0 0 0 .58-3.002a62 62 0 0 1-1.11-6.312a2 2 0 0 0-2.196-1.784l-.105.014H6.897a1.5 1.5 0 0 0-1.36 1.37c-.55 7.692 3.74 15.924 4.611 17.505v.06l.12.23A35.45 35.45 0 0 0 23.272 37.69l.44.25c2 1.06 9.953 5.062 17.386 4.511a1.437 1.437 0 0 0 1.39-1.36V32.58a2.13 2.13 0 0 0-1.666-2.287z");
}

.tm7aidkax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.491 16.994h1l.488 1.695m6.649-7.255v5.315h5.6a6.2 6.2 0 0 0-5.6-5.315");
}

</style>
