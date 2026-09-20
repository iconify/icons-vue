<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq2jeobsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-available-sharp" /></template>
<style>
.aq2jeobsu {
  fill: currentColor;
  d: path("M10.95 18.35L7.4 14.8l1.45-1.45l2.1 2.1l4.2-4.2l1.45 1.45zM3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
