<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmr6pub6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-fill-sharp" /></template>
<style>
.fmr6pub6b {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-9.586l-1.707-1.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1Zm-5.221 7.842a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684m-4.072 5.279a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.676a1 1 0 0 0 .293-.203L9 12.414ZM13 21v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1");
}

</style>
