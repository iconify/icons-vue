<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5vrgbciv"/><path class="k0eafkb-f"/><path class="ztuscy-qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-wind-chime" /></template>
<style>
.k0eafkb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.027s.557-2.896-.706-3.527M24 30.895s.706 4.232-2.823 6.349");
}

.p5vrgbciv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.534 27.104c.63-2.108.75-4.336.349-6.5c-1.397-7.664-8.745-12.746-16.414-11.35A14.11 14.11 0 0 0 9.885 23.135c.001 1.345.197 2.683.582 3.972c.18.599.731 1.009 1.357 1.008h24.352c.626 0 1.179-.41 1.358-1.01");
}

.ztuscy-qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.117 28.779a2.117 2.117 0 0 1-4.234 0h0m-11.998 9.17a10.18 10.18 0 0 0 9.88-2.822l2.823 4.233a10.18 10.18 0 0 1-9.88 2.822z");
}

</style>
