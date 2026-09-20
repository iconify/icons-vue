<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="pxlkwmbqy"/><path class="sf8k2jyhk"/><path class="thhea8b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:linux-mint" /></template>
<style>
.pxlkwmbqy {
  cx: 128px;
  cy: 128px;
  r: 118px;
  fill: var(--svg-color--69b53f, #69b53f);
}

.sf8k2jyhk {
  fill: var(--svg-color--fff, #fff);
  d: path("M128 0C57.308 0 0 57.308 0 128s57.308 128 128 128s128-57.308 128-128S198.692 0 128 0m0 20c59.647 0 108 48.353 108 108s-48.353 108-108 108S20 187.647 20 128S68.353 20 128 20");
}

.thhea8b0f {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M78.5 62.5V153c0 10.772 8.43 19.317 19.153 19.497l.347.003h60c10.772 0 19.317-8.43 19.497-19.153l.003-.347v-50c0-5.365-4.135-9.5-9.5-9.5c-5.273 0-9.357 3.994-9.496 9.224l-.004.276v50.5h-21V103c0-5.365-4.135-9.5-9.5-9.5c-5.273 0-9.357 3.994-9.496 9.224l-.004.276v50.5h-21V103c0-16.726 13.774-30.5 30.5-30.5c7.038 0 13.734 2.515 19.179 6.997l.396.331l.425.368l.434-.376c5.25-4.46 11.71-7.064 18.538-7.302l.526-.014l.502-.004c16.559 0 30.224 13.5 30.496 30l.004.5v50c0 22.027-17.888 40.135-39.834 40.495l-.666.005H98c-22.027 0-40.135-17.888-40.495-39.834L57.5 153V62.5z");
}

</style>
