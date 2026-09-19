<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dv3cz-bnr"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:eight-thirty" /></template>
<style>
.dv3cz-bnr {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m2 33.445V58h-4V35.445a4 4 0 0 1-.913-.719L15.025 38.5L14 34.664l14.186-3.807A3.98 3.98 0 0 1 30 28.554V26h4v2.554c.268.156.519.334.741.545l2.231-.599L38 32.334l-2.11.566A4 4 0 0 1 34 35.445");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
