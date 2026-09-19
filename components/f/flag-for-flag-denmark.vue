<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jwd1l0bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-denmark" /></template>
<style>
.jwd1l0bzw {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m28 30c0 2.375-.299 4.68-.858 6.883H31.017v21.092a27.8 27.8 0 0 1-13.767-4.189V38.883H4.858A28 28 0 0 1 4 32c0-2.375.299-4.68.858-6.883H17.25V8.215a27.8 27.8 0 0 1 13.767-4.19v21.092h28.125C59.701 27.32 60 29.625 60 32");
}

</style>
