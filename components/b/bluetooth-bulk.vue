<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7p2cdcpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bluetooth-bulk" /></template>
<style>
.e7p2cdcpv {
  fill: currentColor;
  d: path("M11 9.586V5a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l2 2a2.414 2.414 0 0 1 0 3.414L13.414 12l2.293 2.293a2.414 2.414 0 0 1 0 3.414l-2 2a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 11 19v-4.586l-2.293 2.293a.999.999 0 1 1-1.414-1.414L10.586 12L7.293 8.707a.999.999 0 1 1 1.414-1.414Zm2 4.828v3.172l1.293-1.293a.414.414 0 0 0 0-.586Zm0-4.828l1.293-1.293a.414.414 0 0 0 0-.586L13 6.414Z");
}

</style>
