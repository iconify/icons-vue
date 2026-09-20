<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sl4aciyyw"/><path class="uyzsf74ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bsi-mobile" /></template>
<style>
.sl4aciyyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-4.32 13v11");
}

.uyzsf74ka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.18 28.295c.674.878 1.52 1.205 2.696 1.205h1.629a2.744 2.744 0 0 0 2.744-2.744v-.012A2.744 2.744 0 0 0 28.505 24h-1.796a2.747 2.747 0 0 1-2.747-2.747a2.753 2.753 0 0 1 2.753-2.753h1.62c1.176 0 2.022.327 2.696 1.205M18.358 24a2.75 2.75 0 1 1 0 5.5H13.82v-11h4.538a2.75 2.75 0 1 1 0 5.5m0 0H13.82");
}

</style>
