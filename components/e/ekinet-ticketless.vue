<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mi4cssbpa"/><path class="tp0l2hb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ekinet-ticketless" /></template>
<style>
.mi4cssbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 28.69H6.444c-.94 0-2.122-.501-2.592-1.314s-.47-1.815 0-2.628s1.653-1.315 2.592-1.315h6.78c6.251 0 8.563-4.123 13.895-4.123H44.5");
}

.tp0l2hb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 26.062h10.6l4.148-1.112H44.5m-22.126-4.497h-4.47c-1.201 0-3.163.353-4.68 2.98m19.595-2.072h2.838v1.725h-2.838zm8.842 0h2.838v1.725h-2.838zm-4.421 0h2.838v1.725H37.24z");
}

</style>
