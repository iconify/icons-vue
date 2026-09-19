<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="obw0d0bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-h" /></template>
<style>
.obw0d0bpb {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m11.664 44.508h-6.023V33.555h-11.28v12.953h-6.025V17.492h6.025v11.063H37.64V17.492h6.023v29.016z");
}

</style>
