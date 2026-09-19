<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="pnwge5-jt"/><circle class="uo6juyzuz"/><path class="utylfab-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hadi" /></template>
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

.pnwge5-jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.533 29.464c.39.656.952 1.207 1.614 1.584s1.424.579 2.187.579s1.524-.202 2.186-.579a4.45 4.45 0 0 0 1.615-1.584M12.394 16.936v10.001m0-4.126a2.5 2.5 0 0 1 2.5-2.5h0a2.5 2.5 0 0 1 2.5 2.5v4.126");
}

.uo6juyzuz {
  cx: 34.731px;
  cy: 17.249px;
  r: 0.75px;
  fill: currentColor;
}

.utylfab-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.731 20.311v6.626m-9.88-2.5a2.5 2.5 0 0 1-2.5 2.5h0a2.5 2.5 0 0 1-2.5-2.5V22.81a2.5 2.5 0 0 1 2.5-2.5h0a2.5 2.5 0 0 1 2.5 2.5m0 4.127v-6.626m7.378 2.5a2.5 2.5 0 0 0-2.5-2.5h0a2.5 2.5 0 0 0-2.5 2.5v1.625a2.5 2.5 0 0 0 2.5 2.5h0a2.5 2.5 0 0 0 2.5-2.5m0 2.501V16.936");
}

</style>
