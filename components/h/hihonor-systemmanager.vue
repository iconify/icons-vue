<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmuu_vhhg"/><path class="wvzk_z75n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hihonor-systemmanager" /></template>
<style>
.bmuu_vhhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.015 5.5c10.03 3.882 13.134 4.912 17.183 7.347c-.247 8.144 0 23.585-17.436 29.653C7.235 37.998 6.919 23.024 6.802 12.4c3.448-2.577 7.11-3.562 17.213-6.9m0 11.867L23.762 42.5");
}

.wvzk_z75n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.802 12.4c4.697 3.044 14.38 4.896 17.213 4.967s11.7-2.242 17.183-4.52");
}

</style>
