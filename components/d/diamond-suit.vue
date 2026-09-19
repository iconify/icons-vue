<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="euu415bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:diamond-suit" /></template>
<style>
.euu415bms {
  fill: currentColor;
  d: path("M62 32L32 62L2.001 32l30-30z");
}

</style>
