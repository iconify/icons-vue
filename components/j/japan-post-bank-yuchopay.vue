<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qfgtaacws"/><path class="exdz_cc2x"/><path class="dvx82bbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-post-bank-yuchopay" /></template>
<style>
.dvx82bbul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.429 36A8.57 8.57 0 0 0 24 27.429v-15.43");
}

.exdz_cc2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.085 33.864c.946.28 1.928.422 2.915.422c5.68 0 10.286-4.605 10.286-10.286S29.681 13.714 24 13.714S13.714 18.319 13.714 24m0 3.428V13.714");
}

.qfgtaacws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.5c0-4.432 3.568-8 8-8h29v29c0 4.432-3.568 8-8 8h-29z");
}

</style>
