<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v0s58abye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-yemen" /></template>
<style>
.v0s58abye {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M5.787 22.167h52.426C59.365 25.229 60 28.541 60 32s-.635 6.771-1.787 9.833H5.787C4.635 38.771 4 35.459 4 32s.635-6.771 1.787-9.833");
}

</style>
