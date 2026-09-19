<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yhdi-4buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-mauritius" /></template>
<style>
.yhdi-4buw {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 2c9.61 0 18.104 4.868 23.148 12.267H8.852C13.896 8.868 22.39 4 32 4m23.148 43.733H8.852A27.83 27.83 0 0 1 4 32h56a27.83 27.83 0 0 1-4.852 15.733");
}

</style>
