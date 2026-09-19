<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r1bq7qb_u"/><circle class="vqfnc3cvj"/><circle class="q3l-sp10m"/><path class="mejadp4kj"/><circle class="tp699vb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:hushed-face" /></template>
<style>
.mejadp4kj {
  fill: currentColor;
  d: path("M51.617 15.373a16.42 16.42 0 0 0-13.492-3.615c-.703.135-.193 2.27.385 2.156c4.17-.748 8.457.4 11.693 3.133c.443.387 1.955-1.205 1.414-1.674m-25.742-3.766a16.42 16.42 0 0 0-13.492 3.615c-.541.469.969 2.063 1.412 1.674a14.24 14.24 0 0 1 11.693-3.133c.578.114 1.09-2.021.387-2.156");
}

.q3l-sp10m {
  cx: 44px;
  cy: 27px;
  r: 5px;
  fill: currentColor;
}

.r1bq7qb_u {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.163 59.5 32 59.5");
}

.tp699vb-e {
  cx: 32px;
  cy: 48px;
  r: 5px;
  fill: currentColor;
}

.vqfnc3cvj {
  cx: 20px;
  cy: 27px;
  r: 5px;
  fill: currentColor;
}

</style>
