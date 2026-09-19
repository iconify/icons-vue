<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="dgkbkqhju"/><path class="qzfzu1b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-clock" /></template>
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

.dgkbkqhju {
  cx: 24px;
  cy: 24px;
  r: 3.332px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qzfzu1b0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 38.614V27.332m1.003-6.51l11.414-7.807a.288.288 0 0 1 .37.439l-9.545 9.78m-6.42-.236l-6.27-7.438a.29.29 0 0 1 .394-.422l7.826 5.765");
}

</style>
