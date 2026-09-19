<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm2s7dbuw"/><path class="klcvwlbfr"/><circle class="bog1cdbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-biotech" /></template>
<style>
.bog1cdbwo {
  cx: 10.5px;
  cy: 8px;
  r: 1.5px;
  fill: currentColor;
}

.klcvwlbfr {
  fill: currentColor;
  d: path("M10.56 5.51C11.91 5.54 13 6.64 13 8c0 .75-.33 1.41-.85 1.87l.59 1.62l.94-.34l.34.94l1.88-.68l-.34-.94l.94-.34l-2.74-7.53l-.94.34l-.34-.94l-1.88.68l.34.94l-.94.35z");
}

.sm2s7dbuw {
  fill: currentColor;
  d: path("M7 19c-1.1 0-2 .9-2 2h14c0-1.1-.9-2-2-2h-4v-2h3c1.1 0 2-.9 2-2h-8c-1.66 0-3-1.34-3-3c0-1.09.59-2.04 1.46-2.56C8.17 9.03 8 8.54 8 8c0-.21.04-.42.09-.62A5.01 5.01 0 0 0 5 12c0 2.76 2.24 5 5 5v2z");
}

</style>
