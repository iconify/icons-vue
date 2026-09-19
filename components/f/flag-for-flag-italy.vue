<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k4zucs-rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-italy" /></template>
<style>
.k4zucs-rn {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-9.834 56.213V5.787C25.228 4.635 28.541 4 32 4s6.771.635 9.833 1.787v52.426C38.771 59.365 35.459 60 32 60s-6.772-.635-9.834-1.787");
}

</style>
