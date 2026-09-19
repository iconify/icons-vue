<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vw9-w3mzl"/><path class="v5pfvab5p"/><path class="mb_ft-b4o"/><circle class="ctvea28pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acea-waidy-wow" /></template>
<style>
.ctvea28pm {
  cx: 24px;
  cy: 24.679px;
  r: 1.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mb_ft-b4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24v18.5H24C13.783 42.5 5.5 34.217 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24");
}

.v5pfvab5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.018c-2.54 0-4.6 2.085-4.6 4.657c0 3.647 3.514 8.045 4.431 9.119a.28.28 0 0 0 .426 0c.896-1.067 4.343-5.472 4.343-9.119c0-2.572-2.06-4.657-4.6-4.657");
}

.vw9-w3mzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.079 28.461c0 5.587-4.512 10.116-10.079 10.116s-10.079-4.53-10.079-10.116C13.921 20.333 24 9.423 24 9.423s10.079 10.91 10.079 19.038");
}

</style>
