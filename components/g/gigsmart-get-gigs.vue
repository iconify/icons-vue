<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pky_5nbsl"/><path class="ky58ut3rx"/><path class="op-zr6b6w"/><path class="mlfbc6bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gigsmart-get-gigs" /></template>
<style>
.ky58ut3rx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.313 11.838a17.2 17.2 0 1 0 5.037 12.16h-8.6");
}

.mlfbc6bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.15 32.6a8.6 8.6 0 0 1-8.6-8.6m8.6-12.9a4.3 4.3 0 0 0 0 8.6a4.3 4.3 0 0 1 0 8.6");
}

.op-zr6b6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.61 27.34a12.9 12.9 0 1 1-23.63-9.788");
}

.pky_5nbsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.65 24c0-11.874 9.626-21.5 21.5-21.5m15.204 36.703A21.5 21.5 0 0 1 26.15 45.5");
}

</style>
