<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ugaf8fbfz"/><path class="u-0jefbqy"/><circle class="qu5fo0bdu"/><circle class="p1rtd_bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:globeone" /></template>
<style>
.p1rtd_bju {
  cx: 42.089px;
  cy: 25.543px;
  r: 3.326px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qu5fo0bdu {
  cx: 22.344px;
  cy: 5.826px;
  r: 3.326px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u-0jefbqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.772 33.66A19.956 19.956 0 1 1 14.108 7.457m16.231-.283a19.96 19.96 0 0 1 10.433 10.253");
}

.ugaf8fbfz {
  cx: 22.542px;
  cy: 25.543px;
  r: 7.982px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
