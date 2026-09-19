<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kh2_q2bwp"/><path class="vue9d3b8c"/><path class="szjsorodr"/><circle class="qcyspxbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dreamer" /></template>
<style>
.kh2_q2bwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.769 39.615a7.45 7.45 0 0 1-6.166 3.885a6.06 6.06 0 0 1-6.167-3.885c-.813-1.734-2.372-5.233-2.372-5.233l-8.882-.005a6.027 6.027 0 1 1 0-12.054s.99-6.13 6.136-6.13h4.02l8.656-6.958V20.21l4.774 12.292c1.026 2.447 1.273 4.912 0 7.113");
}

.qcyspxbkn {
  cx: 20.301px;
  cy: 22.575px;
  r: 1.474px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.szjsorodr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.556 11.903L13.666 4.5l3.706 9.13m15.693 1.803s4.394 7.258 6.218 12.61c1.591 4.667-.66 5.583-.66 5.583");
}

.vue9d3b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.476 11.848h-7.575c-3.974 0-5.938 2.697-5.748 6.24");
}

</style>
