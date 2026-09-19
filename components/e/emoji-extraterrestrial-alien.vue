<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y54a9rfhz"/><path class="ro9di2bsa"/><path class="uptjgdcsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-extraterrestrial-alien" /></template>
<style>
.ro9di2bsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5c-5.674 0-8.356-5.428-9.162-7.463a3.9 3.9 0 0 0-.82-1.28c-1.314-1.362-4.533-5.435-4.533-12.635C9.485 10.678 16.742 5.5 24 5.5s14.515 5.178 14.515 15.622c0 7.241-2.915 10.954-4.35 12.44a6.3 6.3 0 0 0-1.157 1.638c-2.813 5.811-6.099 7.3-9.008 7.3");
}

.uptjgdcsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.14 28.083c-1.39 2.583-3.731 3.987-5.227 3.137s-1.58-3.633-.189-6.216s3.732-3.988 5.228-3.138s1.58 3.634.189 6.217");
}

.y54a9rfhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.371 35.986c.3.283 1.63 1.473 3.563 1.345c1.568-.103 2.62-1.014 2.969-1.345m-12.242-7.903c1.392 2.583 3.732 3.987 5.228 3.137s1.58-3.633.189-6.216s-3.732-3.988-5.228-3.138s-1.58 3.634-.189 6.217");
}

</style>
