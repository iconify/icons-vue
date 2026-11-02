<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz904xiqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-9-fill" /></template>
<style>
.xz904xiqp {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m11 0V7a1 1 0 0 0-2 0v4H7a1 1 0 0 0 0 2h5a1 1 0 0 0 1-1");
}

</style>
