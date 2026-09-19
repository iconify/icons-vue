<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rwhc-tbxc"/><circle class="o0sgio2ac"/><path class="e8ubleb_k"/><path class="en4i1lgmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bike" /></template>
<style>
.e8ubleb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.742 16.845l-9.265 11.908H11.329l9.299-11.908z");
}

.en4i1lgmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.671 28.753l-5.387-16.335H27.32m-7.584.652l3.741 15.683m-6.16-15.683h5.044");
}

.o0sgio2ac {
  cx: 11.329px;
  cy: 28.753px;
  r: 6.829px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rwhc-tbxc {
  cx: 36.671px;
  cy: 28.753px;
  r: 6.829px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
