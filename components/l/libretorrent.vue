<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9ilzv9aj"/><circle class="bfh2qybue"/><circle class="wfsdqxseq"/><circle class="gz2f0hyhm"/><path class="oxwq5bcow"/><path class="qqbdall_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libretorrent" /></template>
<style>
.bfh2qybue {
  cx: 22.561px;
  cy: 6.832px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gz2f0hyhm {
  cx: 9.278px;
  cy: 38.721px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9ilzv9aj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.289 7.314A19.01 19.01 0 0 0 6.283 35.637m34.789-14.105A19.03 19.03 0 0 0 26.833 7.314M12.272 41.808a19.008 19.008 0 0 0 28.806-11.703");
}

.oxwq5bcow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.243 34.886c7.228-6.757 13.616-9.63 24.018-9.332");
}

.qqbdall_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.548 11.132c-.091 7.61-1.006 15.314-10.148 24.634");
}

.wfsdqxseq {
  cx: 41.561px;
  cy: 25.832px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
