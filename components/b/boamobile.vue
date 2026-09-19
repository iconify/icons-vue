<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqx1elb0c"/><path class="tiyx7omux"/><path class="ucfoyq-tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boamobile" /></template>
<style>
.gqx1elb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 17.795V5.38L24 11.587v24.826L13.25 42.62V30.206");
}

.tiyx7omux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.749 30.207L45.5 24l-10.75-6.207l-21.5 12.413L2.5 24l10.751-6.207");
}

.ucfoyq-tj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.999 36.412l10.751 6.207V30.206l-21.5-12.413V5.38l10.751 6.207");
}

</style>
