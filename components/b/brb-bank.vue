<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="klrjktb-x"/><path class="k3mnphb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brb-bank" /></template>
<style>
.k3mnphb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.111 39.415c0-13.653-10.139-24.938-23.298-26.735");
}

.klrjktb-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.356 39.415h27.397L42.5 8.585H9.443L5.558 33.82a4.855 4.855 0 0 0 4.798 5.594m6.178-9.757l16.187-13.321");
}

</style>
