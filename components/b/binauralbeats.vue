<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="pn8finb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:binauralbeats" /></template>
<style>
.pn8finb1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.683 25.543a4.41 4.41 0 0 1 4.409-4.408h0a4.41 4.41 0 0 1 4.408 4.408v2.865a4.41 4.41 0 0 1-4.408 4.409h0a4.41 4.41 0 0 1-4.409-4.409m0 4.409V15.183M18.774 24a4.408 4.408 0 1 1 0 8.817H11.5V15.183h7.274a4.408 4.408 0 1 1 0 8.817m0 0H11.5");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
