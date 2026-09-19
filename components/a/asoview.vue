<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6brivsds"/><path class="y2obkqb7x"/><path class="v8e22fbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asoview" /></template>
<style>
.v8e22fbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.251 29.641c2.258-3.337 4.248-7.223 5.408-11.552a10 10 0 0 0-5.408-11.64");
}

.x6brivsds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.74 39.262c4.618-4.066 11.332-11.518 13.919-21.174A10 10 0 0 0 23.999 5.5c-1.521 0-2.964.34-4.255.948");
}

.y2obkqb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.498 35.051c3.812-4.224 7.802-10.025 9.661-16.963a10 10 0 1 0-19.318 0C9.511 31.783 21.483 41.046 24 42.5c2.518-1.454 14.49-10.716 18.159-24.412A10 10 0 0 0 32.499 5.5c-1.521 0-2.964.34-4.255.948");
}

</style>
