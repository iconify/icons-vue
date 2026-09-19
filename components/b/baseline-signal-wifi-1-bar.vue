<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv4-lbxz"/><path class="omk54zbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-wifi-1-bar" /></template>
<style>
.omk54zbus {
  fill: currentColor;
  d: path("M6.67 14.86L12 21.49v.01l.01-.01l5.33-6.63C17.06 14.65 15.03 13 12 13s-5.06 1.65-5.33 1.86");
}

.qsv4-lbxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M12.01 21.49L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l11.63 14.49l.01.01z");
}

</style>
