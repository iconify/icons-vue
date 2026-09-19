<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w6jq81bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-germany" /></template>
<style>
.w6jq81bgw {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M6.254 21h51.492q.368.864.679 1.756H5.575q.311-.892.679-1.756M32 60C20.083 60 9.888 52.514 5.853 42h52.294C54.112 52.514 43.917 60 32 60");
}

</style>
