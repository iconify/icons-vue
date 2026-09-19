<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="huqmjj_lb"/><path class="shfwhgb_x"/><path class="dr_4_zbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-bookmark-tabs" /></template>
<style>
.dr_4_zbdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.076 13.18h-7.47l.014-7.68m10.633 15.359l-1.285-1.732l1.285-1.731h5.201v3.462zm-3.491 13.236l-1.285-1.732l1.285-1.73h5.201v3.462zm3.805-3.487v-9.67M9.96 9.326h10.347M9.96 15.232h19.213M9.96 20.405h19.213M9.96 26.318h19.213M9.96 32.23h19.213");
}

.huqmjj_lb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.567 17.193V8.991h-7.456M10.037 39.01v3.49h26.53v-8.147");
}

.shfwhgb_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.076 30.632V12.956L25.62 5.5H6.546v33.51h26.53v-4.887");
}

</style>
