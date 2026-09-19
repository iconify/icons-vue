<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w2x-yy-mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auto-ru" /></template>
<style>
.w2x-yy-mh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.912 30.329H16.216m-6.86 0H7.952A3.45 3.45 0 0 1 4.5 26.877v-5.552l4.77-5.418c.548-.623 1.012-1.247 2.152-1.247h13.311c.8 0 1.66.17 2.32.624l7.216 4.964l6.97 1.66c1.703.405 2.261 1.201 2.261 2.272v2.682c0 1.92-1.54 3.467-3.453 3.467H37.77m.055-.487a3.49 3.49 0 0 1-3.484 3.498h0c-1.924 0-3.484-1.566-3.484-3.498s1.56-3.498 3.484-3.498s3.484 1.566 3.484 3.498m-21.556 0a3.49 3.49 0 0 1-3.484 3.498h0c-1.924 0-3.484-1.566-3.484-3.498s1.56-3.498 3.484-3.498s3.484 1.566 3.484 3.498");
}

</style>
