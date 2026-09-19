<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="gzgpk8gsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbl-digipass" /></template>
<style>
.gzgpk8gsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.102 24c.001 6.683-5.415 12.1-12.098 12.102H24c-6.683.001-12.1-5.415-12.102-12.098V24c-.001-6.683 5.415-12.1 12.098-12.102H24c6.683-.001 12.1 5.415 12.102 12.098z");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
