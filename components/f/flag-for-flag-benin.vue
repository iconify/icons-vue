<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b35eibb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-benin" /></template>
<style>
.b35eibb4k {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m28 30H24v26.829q-.93-.277-1.833-.616V5.787A27.9 27.9 0 0 1 32 4c15.439 0 28 12.561 28 28");
}

</style>
