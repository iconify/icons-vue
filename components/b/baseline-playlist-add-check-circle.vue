<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv6x4hbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-playlist-add-check-circle" /></template>
<style>
.pv6x4hbwo {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2M7 7h7v2H7zm0 3h7v2H7zm3 5H7v-2h3zm4.05 3.36l-2.83-2.83l1.41-1.41l1.41 1.41L17.59 12L19 13.41z");
}

</style>
