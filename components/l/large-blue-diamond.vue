<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uktz89k5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:large-blue-diamond" /></template>
<style>
.uktz89k5k {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63 32L32 62.999L1 32L32 1");
}

</style>
