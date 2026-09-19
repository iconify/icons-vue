<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b2_hc7bjn"/><path class="m8-vtr_wf"/><circle class="io-p46pmv"/><circle class="wfjuqubhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:grinning-face" /></template>
<style>
.b2_hc7bjn {
  fill: currentColor;
  d: path("M32 2C15.43 2 2 15.43 2 32s13.43 30 30 30s30-13.43 30-30S48.57 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

.io-p46pmv {
  cx: 20.5px;
  cy: 23px;
  r: 5px;
  fill: currentColor;
}

.m8-vtr_wf {
  fill: currentColor;
  d: path("M47.783 34.006H16.215c-.785 0-1.505-.09-1.912.43C10.394 39.422 14.993 54 31.999 54c17.007 0 21.606-14.578 17.696-19.564c-.406-.52-1.127-.43-1.912-.43M32 52.182c-2.913 0-5.483-.561-7.713-1.517c2.152-1.032 4.711-1.663 7.713-1.663s5.563.631 7.713 1.663c-2.229.956-4.799 1.517-7.713 1.517M47.006 40H16.994c-2.001 0-2.001-4 .053-4h29.906c2.053 0 2.053 4 .053 4");
}

.wfjuqubhe {
  cx: 43.5px;
  cy: 23px;
  r: 5px;
  fill: currentColor;
}

</style>
