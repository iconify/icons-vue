<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ujopowhay"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:four-thirty" /></template>
<style>
.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

.ujopowhay {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m11.143 44L34 36.857V58h-4V35.445c-1.19-.693-2-1.969-2-3.445c0-.348.059-.68.142-1.001L26 28.857L28.855 26L30 27.145V26h4v2.555A3.98 3.98 0 0 1 36 32c0 .348-.059.68-.143 1.002L46 43.143z");
}

</style>
