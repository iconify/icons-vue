<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bx7syxi9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-colombia" /></template>
<style>
.bx7syxi9f {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 2c15.439 0 28 12.561 28 28H4C4 16.561 16.561 4 32 4m25 41H7c-.336-.654-.715-1.318-1-2h52c-.285.682-.664 1.346-1 2");
}

</style>
