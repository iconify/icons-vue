<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sy-jt8bay"/><path class="l3qmrpb_b"/><path class="jukf615wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:accubattery" /></template>
<style>
.jukf615wp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 15.58C14.07 13 16.48 12 19.26 12c6.9 0 7.66 4.57 13.33 4.57c3.64 0 4.42-2 4.42-2M23.75 30.65l2.24-3.98l-3.98.34l2.24-3.99");
}

.l3qmrpb_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.88 4.5h10.23a2.27 2.27 0 0 1 2.29 2.27v1.48H34a3 3 0 0 1 3 2.95v29.3a3 3 0 0 1-3 3H14a3 3 0 0 1-3-3V11.32a3 3 0 0 1 2.94-3.07h2.66V6.79a2.28 2.28 0 0 1 2.26-2.29Z");
}

.sy-jt8bay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.82a2.15 2.15 0 0 0-.87.18l-5.82 2.38a.85.85 0 0 0-.52.78v5.13c0 4.58 5.19 7.56 7.21 7.56s7.21-3 7.21-7.56v-5.13a.85.85 0 0 0-.52-.78L24.87 19a2 2 0 0 0-.87-.18");
}

</style>
