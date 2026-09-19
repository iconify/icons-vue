<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rm10n1bpb"/><path class="qdq_k38dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iegeek-cam" /></template>
<style>
.qdq_k38dz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.48L24 8.621L42.5 24.48");
}

.rm10n1bpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.254 19.548v7.574c0 6.769 5.706 12.256 12.746 12.256s12.746-5.487 12.746-12.256H24");
}

</style>
