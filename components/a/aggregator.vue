<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_3une5aj"/><circle class="tb4-c-bpc"/><circle class="jhz5eubck"/><path class="csrz0b1tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aggregator" /></template>
<style>
.csrz0b1tk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.66 20.168A11.01 11.01 0 0 1 27.832 35.34");
}

.jhz5eubck {
  cx: 18.495px;
  cy: 29.505px;
  r: 4.004px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q_3une5aj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.245 26.002q.13-.996.14-2.002a17 17 0 0 0-.14-2.002l4.334-3.393a1 1 0 0 0 .25-1.311l-4.104-7.117a1 1 0 0 0-1.251-.44l-5.115 2.061a15.7 15.7 0 0 0-3.463-2.002l-.771-5.435a1 1 0 0 0-1.001-.86h-8.228a1 1 0 0 0-1.001.86l-.77 5.435a15.4 15.4 0 0 0-3.464 2.002L9.526 9.736a1 1 0 0 0-1.252.44L4.17 17.294a1 1 0 0 0 .25 1.312l4.325 3.393A17 17 0 0 0 8.605 24q.01 1.006.14 2.002L4.42 29.395a1 1 0 0 0-.25 1.311l4.103 7.117a1 1 0 0 0 1.252.44l5.115-2.061a15.7 15.7 0 0 0 3.463 2.002l.77 5.435a1 1 0 0 0 1.002.86h8.208a1 1 0 0 0 1-.86l.772-5.435a15.4 15.4 0 0 0 3.463-2.002l5.115 2.062a1 1 0 0 0 1.251-.44l4.104-7.118a1 1 0 0 0-.25-1.31z");
}

.tb4-c-bpc {
  cx: 24px;
  cy: 24px;
  r: 12.012px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
