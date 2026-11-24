<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p703xuuca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-minus-corner-fill-sharp" /></template>
<style>
.p703xuuca {
  fill: currentColor;
  d: path("M22 11a1 1 0 0 1-1 1h-9.586l-1.707-1.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Zm-7-1a2 2 0 1 0 .001-3.999A2 2 0 0 0 15 10m-6 2.414l2.707 2.707a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.676a1 1 0 0 0 .293-.203ZM15 16h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
