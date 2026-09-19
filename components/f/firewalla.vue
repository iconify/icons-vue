<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n59w2yl_p"/><path class="oqk1ezb0m"/><path class="uybc9w8kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firewalla" /></template>
<style>
.n59w2yl_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.801 10.555c2.418 7.407-2.33 17.08-5.772 21");
}

.oqk1ezb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.327 40.16c8.401-17.754-14.21-21.544-3.885-35.66c.262 5.686 12.287 6.012 12.287 18.69s-12.7 20.31-12.7 20.31c-19.04-14.85-12.853-26.845-6.383-32.334c4.51 8.692 3.876 11.078 1.317 16.322");
}

.uybc9w8kj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.029 43.5c5.707-16.715-10.482-11.491-9.82-28.59");
}

</style>
