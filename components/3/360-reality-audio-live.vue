<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gc2xf49jl"/><path class="tfa22ob4s"/><path class="yo2zlkbtf"/><circle class="hm5f0-0pf"/><circle class="e5vvouqvc"/><circle class="fna591k-t"/><path class="ub9g-sbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:360-reality-audio-live" /></template>
<style>
.e5vvouqvc {
  cx: 38.495px;
  cy: 9.505px;
  r: 2.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fna591k-t {
  cx: 35.302px;
  cy: 28.83px;
  r: 2.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gc2xf49jl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.946 10.769c6.683 8.558 5.935 20.756-1.743 28.434c-7.585 7.585-19.6 8.419-28.16 1.954m-4.2-4.2c-6.464-8.56-5.63-20.575 1.954-28.16c7.68-7.68 19.882-8.426 28.44-1.74");
}

.hm5f0-0pf {
  cx: 10.211px;
  cy: 37.789px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tfa22ob4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.1 30.713a13.5 13.5 0 0 1-3.383 5.662c-4.554 4.554-11.7 5.337-17.055 1.76c7.365 5.48 17.634 4.73 24.126-1.76c6.555-6.555 7.247-16.95 1.618-24.314");
}

.ub9g-sbse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.801 31.02a16 16 0 0 1-7.048 10.335M6.646 19.247a16 16 0 0 1 2.151-2.671c6.249-6.249 16.379-6.249 22.627 0h0a16 16 0 0 1 4.643 10.137");
}

.yo2zlkbtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.67 26.679a13.5 13.5 0 0 0-3.953-9.396c-5.272-5.273-13.82-5.273-19.092 0c-4.547 4.546-5.34 11.677-1.777 17.03c-5.462-7.364-4.706-17.618 1.777-24.101C18.18 3.658 28.57 2.965 35.936 8.59");
}

</style>
