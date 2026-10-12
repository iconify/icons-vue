<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3iyxx77h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lily" /></template>
<style>
.l3iyxx77h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.56 9.03l-2.27.94q-.69.28-.59 1.02l.32 2.43q.11.74-.49.28l-1.94-1.49q-.59-.46-1.18 0L9.47 13.7q-.59.46-.49-.28l.32-2.43q.1-.74-.59-1.02l-2.27-.94q-.69-.28 0-.56l2.27-.94q.69-.28.59-1.02l-.32-2.43q-.11-.74.49-.28l1.94 1.49q.59.46 1.18 0l1.94-1.49q.6-.46.49.28l-.32 2.43q-.1.74.59 1.02l2.27.94q.69.28 0 .56M12 8.75l1.75-3.03M12 8.75l1.75 3.03M12 8.75H8.5m3.5 3v9.5m0-.25c.75-3.25 3.5-5.25 7.5-5.25C19 19 16.25 21 12 21");
}

</style>
