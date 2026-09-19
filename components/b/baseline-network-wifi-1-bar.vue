<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygt2zab-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-network-wifi-1-bar" /></template>
<style>
.ygt2zab-y {
  fill: currentColor;
  d: path("M12 4C7.31 4 3.07 5.9 0 8.98L12 21L24 8.98A16.88 16.88 0 0 0 12 4m3.32 10.84C14.34 14.3 13.2 14 12 14s-2.34.3-3.32.84L2.92 9.07C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07z");
}

</style>
