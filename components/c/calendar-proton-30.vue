<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_vqhozqx"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-30" /></template>
<style>
.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.j_vqhozqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.007 28.91a4.98 4.98 0 0 0 5 5a4.825 4.825 0 0 0 4.815-5v-5a4.943 4.943 0 0 0-4.815-5a5.1 5.1 0 0 0-5 5Zm-6.011-2.593A3.715 3.715 0 0 1 18.7 30.02a3.715 3.715 0 0 1-3.704 3.703h-1.482c-2.592 0-3.518-.37-4.63-1.296m.001-12.221c1.11-.926 2.222-1.296 4.63-1.296h1.481a3.715 3.715 0 0 1 3.704 3.703a3.715 3.715 0 0 1-3.704 3.704h-3.704");
}

.orx8z1bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138V15.819a3.14 3.14 0 0 0-3.138-3.138H4.5");
}

.wtoegrbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.138V11.862a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.276a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
