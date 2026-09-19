<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pdt3y2brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-i" /></template>
<style>
.pdt3y2brd {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.431 2 32s13.432 30 30 30s30-13.432 30-30C62 15.431 48.568 2 32 2m3.012 44.508h-6.023V17.492h6.023z");
}

</style>
