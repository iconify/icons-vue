<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="soc712zwr"/><path class="izq1bhbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fanduel-sportsbook" /></template>
<style>
.izq1bhbop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.604 23.777c3.981-2 8.3-3.15 12.707-3.384");
}

.soc712zwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.06 41.939s-6.952-4.785-12.452-14.311S5.44 9.689 5.44 9.689s7.62-3.628 18.62-3.628q.885 0 1.737.03m3.28.221C37.278 7.134 42.56 9.69 42.56 9.69s-.575 8.398-6.048 17.94c-3.408 5.94-7.4 10.03-9.926 12.272");
}

</style>
