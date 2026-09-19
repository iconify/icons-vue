<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjs9ccc1a"/><path class="g2o_l2bxt"/><path class="q30bv-ody"/><path class="qfk5tbcmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:allevents" /></template>
<style>
.g2o_l2bxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.05 19.05a7 7 0 1 1-1.812 6.761");
}

.mjs9ccc1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.289 32.25v-16.5a4 4 0 0 0-2-3.464L26 4.036a4 4 0 0 0-4 0l-14.289 8.25a4 4 0 0 0-2 3.464v16.5a4 4 0 0 0 2 3.464L22 43.964a4 4 0 0 0 4 0l14.289-8.25a4 4 0 0 0 2-3.464");
}

.q30bv-ody {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 24a7 7 0 1 0-2.05 4.95");
}

.qfk5tbcmu {
  fill: none;
  stroke: currentColor;
  d: path("M38 24H24m0 0H12.05m-1.811 1.812C10 24.75 11 24 12.05 24");
}

</style>
