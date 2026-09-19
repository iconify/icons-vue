<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkpftex1i"/><circle class="i_bls13id"/><path class="ow2ivwb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:applicationsinfo" /></template>
<style>
.i_bls13id {
  cx: 19.12px;
  cy: 18.22px;
  r: 0.75px;
  fill: currentColor;
}

.mkpftex1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.12 12.79c6.191 0 11.21 5.019 11.21 11.21s-5.019 11.21-11.21 11.21S7.91 30.191 7.91 24s5.019-11.21 11.21-11.21");
}

.ow2ivwb4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.12 22.08v8.45M8.5 8.5a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4V22.678a4 4 0 0 0-1.172-2.828L32.152 9.672A4 4 0 0 0 29.324 8.5z");
}

</style>
