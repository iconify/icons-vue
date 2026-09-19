<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv4-lbxz"/><path class="b0yw16bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-wifi-3-bar" /></template>
<style>
.b0yw16bmx {
  fill: currentColor;
  d: path("m3.53 10.95l8.46 10.54l.01.01l.01-.01l8.46-10.54C20.04 10.62 16.81 8 12 8s-8.04 2.62-8.47 2.95");
}

.qsv4-lbxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M12.01 21.49L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l11.63 14.49l.01.01z");
}

</style>
