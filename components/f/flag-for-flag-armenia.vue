<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qwdwy_bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-armenia" /></template>
<style>
.qwdwy_bps {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M5.787 22.167h52.426q.369.983.664 2H5.123q.296-1.017.664-2M32 60c-11.601 0-21.575-7.092-25.818-17.167h51.636C53.574 52.908 43.601 60 32 60");
}

</style>
