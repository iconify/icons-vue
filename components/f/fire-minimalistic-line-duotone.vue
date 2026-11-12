<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="skbj383bo"/><path class="z2s4-80vv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-minimalistic-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skbj383bo {
  d: path("M20 13.504C20 17.6439 16.4183 21 12 21C7.58172 21 4 17.6439 4 13.504C4 8.51143 6.9046 4.90436 9.08645 3.11539C9.46972 2.80113 9.97151 3.17868 9.83483 3.64868C8.31688 8.86844 10.1975 9.92086 11.4286 9.75607C13.4178 9.75607 14.9742 7.3229 15.7212 5.63288C15.8683 5.30006 16.3017 5.18584 16.562 5.44436C17.9654 6.83811 20 9.76257 20 13.504Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z2s4-80vv {
  stroke-linejoin: round;
  d: path("M19.5234 16.0587C19.8318 15.2614 20 14.4011 20 13.504C20 9.76257 17.9654 6.83811 16.562 5.44436C16.3017 5.18584 15.8683 5.30006 15.7212 5.63288C14.9742 7.3229 13.4178 9.75607 11.4286 9.75607C10.1975 9.92086 8.31688 8.86844 9.83483 3.64868C9.97151 3.17868 9.46972 2.80113 9.08645 3.11539C6.9046 4.90436 4 8.51143 4 13.504C4 14.4011 4.16818 15.2614 4.4766 16.0587");
}

</style>
