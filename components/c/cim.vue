<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s_wntnb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cim" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s_wntnb9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.371 19.319v9.362m2.768-.01v-9.352l4.68 9.362l4.681-9.347v9.347m-14.798-3.14v.039a3.1 3.1 0 0 1-3.101 3.1h0a3.1 3.1 0 0 1-3.101-3.1v-3.16a3.1 3.1 0 0 1 3.101-3.1h0a3.1 3.1 0 0 1 3.101 3.1v.038");
}

</style>
