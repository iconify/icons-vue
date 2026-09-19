<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x27v_173l"/><path class="uyiximbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googletv" /></template>
<style>
.uyiximbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.375 17.219a2.906 2.906 0 0 0-2.906-2.906h-3.291M34.656 39.5a2.906 2.906 0 0 0 2.906-2.906v-3.291M4.625 30.781a2.906 2.906 0 0 0 2.906 2.906h3.291M13.344 8.5a2.906 2.906 0 0 0-2.906 2.906v3.291");
}

.x27v_173l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.78 39.5H9.22a4.57 4.57 0 0 1-4.595-4.532V13.032A4.57 4.57 0 0 1 9.22 8.5h29.56a4.57 4.57 0 0 1 4.595 4.532v21.936A4.57 4.57 0 0 1 38.78 39.5m-28.342-5.812h27.124V14.311H10.439Z");
}

</style>
