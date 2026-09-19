<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z7-c7pzcr"/><path class="xg264cbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aerial-tv" /></template>
<style>
.xg264cbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.27 33.628h5.443l-2.721-4.004z");
}

.z7-c7pzcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 8.802h37v24.835H29.467L24 24.407l-5.467 9.23H5.5zm14.053 27.352l-2.054 3.02l13.002.024l-2.07-3.044z");
}

</style>
