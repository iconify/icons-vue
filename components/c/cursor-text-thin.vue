<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nfan2abwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cursor-text-thin" /></template>
<style>
.nfan2abwj {
  fill: currentColor;
  d: path("M180 208a4 4 0 0 1-4 4h-16a36 36 0 0 1-32-19.54A36 36 0 0 1 96 212H80a4 4 0 0 1 0-8h16a28 28 0 0 0 28-28v-44h-20a4 4 0 0 1 0-8h20V80a28 28 0 0 0-28-28H80a4 4 0 0 1 0-8h16a36 36 0 0 1 32 19.54A36 36 0 0 1 160 44h16a4 4 0 0 1 0 8h-16a28 28 0 0 0-28 28v44h20a4 4 0 0 1 0 8h-20v44a28 28 0 0 0 28 28h16a4 4 0 0 1 4 4");
}

</style>
