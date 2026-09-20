<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u4zr43bhi"/><path class="k_ndklyla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-explorer-compose" /></template>
<style>
.k_ndklyla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.967 24c0 3.289-2.671 5.955-5.967 5.955S18.033 27.289 18.033 24s2.671-5.955 5.967-5.955s5.967 2.666 5.967 5.955");
}

.u4zr43bhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.213 34.25L24 44.5l17.787-10.25v-20.5L24 3.5L6.213 13.75zm.437-20.248l11.967 6.895M24 44V30.203m17.35-16.201l-11.967 6.895");
}

</style>
