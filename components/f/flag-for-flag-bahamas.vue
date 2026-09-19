<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hl8dkssgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-bahamas" /></template>
<style>
.hl8dkssgk {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-8.419 39.833L12.934 52.479a28 28 0 0 1-1.414-1.414L30.586 32L11.52 12.934a29 29 0 0 1 1.414-1.414L23.58 22.167h34.633C59.365 25.228 60 28.54 60 32s-.635 6.772-1.787 9.833z");
}

</style>
