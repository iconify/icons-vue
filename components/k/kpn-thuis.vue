<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hw6x7sadh"/><path class="l63frwb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kpn-thuis" /></template>
<style>
.hw6x7sadh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.063 17.43L25.723 5.172a2.55 2.55 0 0 0-3.447 0L8.936 17.43a2 2 0 0 0-.646 1.473V41.5a2 2 0 0 0 2 2h27.42a2 2 0 0 0 2-2V18.903a2 2 0 0 0-.646-1.473Z");
}

.l63frwb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.776 30.894a4.314 4.314 0 0 0-5.512-.015v.015m2.745 1.766a1.73 1.73 0 1 0 1.73 1.73a1.73 1.73 0 0 0-1.73-1.73m5.398-4.757a8.48 8.48 0 0 0-10.796 0M32 24.764a12.54 12.54 0 0 0-16 0");
}

</style>
