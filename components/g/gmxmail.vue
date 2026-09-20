<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qk8q6g9_k"/><path class="yjm1qhb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gmxmail" /></template>
<style>
.qk8q6g9_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.89 22.467a3.11 3.11 0 0 0-3.276-3.105c-1.68.088-2.941 1.597-2.941 3.28v2.881a3.109 3.109 0 0 0 6.218 0h-3.11m6.5 3.109v-9.274l4.629 9.284l4.628-9.27v9.27m3.39-9.284L35.037 24l-3.109 4.642m6.218-9.284L35.037 24l3.109 4.642");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
