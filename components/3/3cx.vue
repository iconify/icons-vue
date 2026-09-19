<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhn53mbzh"/><path class="q_4gw_bvl"/><path class="wh_hk5ujq"/><path class="u3wan80np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3cx" /></template>
<style>
.jhn53mbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-8.64 12.357L38 30.143m0-12.286l-8.14 12.286");
}

.q_4gw_bvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.14 26.487a4.07 4.07 0 0 1-4.05 3.656h0a4.07 4.07 0 0 1-4.07-4.07v-4.146a4.07 4.07 0 0 1 4.07-4.07h0a4.07 4.07 0 0 1 4.05 3.654");
}

.u3wan80np {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 18.883c.85-.708 1.767-1.032 3.823-1.026l.478.003a3.07 3.07 0 0 1 3.07 3.07h0a3.07 3.07 0 0 1-3.07 3.071m-2.361.001h2.361");
}

.wh_hk5ujq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.16 24.001l-1.91-1.867v3.735zm-18.159 5.106c.849.71 1.764 1.036 3.82 1.036h.48a3.07 3.07 0 0 0 3.07-3.07h0A3.07 3.07 0 0 0 14.302 24");
}

</style>
