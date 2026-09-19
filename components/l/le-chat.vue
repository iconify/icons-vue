<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ov9heac4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:le-chat" /></template>
<style>
.ov9heac4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.786 21.208v-5.583h5.57V10.04h5.572v22.334H43.5v5.584H26.786v-5.584h5.571v-5.583h-5.571v5.583h-5.572v-5.583h-5.571v5.583h5.571v5.584H4.5v-5.584h5.572V10.041h5.571v5.584h5.571v5.583z");
}

</style>
