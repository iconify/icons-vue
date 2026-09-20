<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjoxh-bsf"/><path class="z_2vucyrk"/><path class="ydqthzbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ccgt" /></template>
<style>
.sjoxh-bsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.6 19.3v8.8c0 1.6-1.3 2.9-2.9 2.9q-1.2 0-2.1-.9");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

.z_2vucyrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.6 19.3zc1.6 0 2.9 1.3 2.9 2.9v1.9c0 1.6-1.3 2.9-2.9 2.9s-2.9-1.3-2.9-2.9v-1.9c0-1.6 1.3-2.9 2.9-2.9m7.2-2.4v8.8c0 .8.7 1.5 1.5 1.5h.4m-3.5-7.9h3.1m-22.8 6.3c-.5.9-1.5 1.5-2.6 1.5c-1.6 0-2.9-1.3-2.9-2.9v-1.9c0-1.6 1.3-2.9 2.9-2.9c1.1 0 2 .6 2.6 1.5m8.5 4.7c-.5.9-1.5 1.5-2.6 1.5c-1.6 0-2.9-1.3-2.9-2.9v-1.9c0-1.6 1.3-2.9 2.9-2.9c1.1 0 2 .6 2.6 1.5");
}

</style>
