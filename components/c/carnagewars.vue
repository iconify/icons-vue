<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="galspl_ov"/><path class="gthnddcpy"/><circle class="mhcd2tn4b"/><circle class="ool_bg7_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carnagewars" /></template>
<style>
.galspl_ov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.368 29.384c-1.17-2.444-3.615-6.683-2.646-11.359s5.354-9.79 11.366-12.421c6.012-2.63 13.652-2.776 19.25.203c5.6 2.979 9.157 9.083 9.969 13.552c.812 4.47-1.122 7.303-2.31 9.185s-1.631 2.812-1.742 4.096s.11 2.923-1.07 3.72s-3.764.753-5.056 2.007c-1.291 1.255-1.291 3.808-4.325 5.085c-3.033 1.277-9.1 1.277-12.132-.096s-3.033-4.118-4.318-5.49s-3.852-1.374-5.07-1.935c-1.217-.56-1.085-1.682-.967-2.568c.119-.885.222-1.535-.949-3.979");
}

.gthnddcpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.163 32.947c-.535.43-1.385 1.145-1.962 1.99c-.577.846-.88 1.822-.848 2.581c.031.76.397 1.302.973 1.475c.577.172 1.365-.027 1.764-.387c.4-.36.41-.882.478-1.208c.067-.326.193-.456.312-.455s.232.135.289.457c.056.321.056.83.456 1.192s1.2.576 1.836.408s1.11-.718 1.148-1.562s-.359-1.985-.898-2.837c-.54-.853-1.22-1.42-1.673-1.768s-.677-.479-.899-.47c-.222.007-.44.153-.976.584");
}

.mhcd2tn4b {
  cx: 15.056px;
  cy: 27.292px;
  r: 4.807px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ool_bg7_i {
  cx: 32.973px;
  cy: 27.129px;
  r: 4.807px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
