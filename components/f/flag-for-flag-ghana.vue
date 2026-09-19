<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wdoalspiw"/><path class="a_d14drdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-ghana" /></template>
<style>
.a_d14drdr {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M5.787 22.167h52.426A27.9 27.9 0 0 1 60 32c0 3.459-.635 6.771-1.787 9.834H5.787A27.9 27.9 0 0 1 4 32c0-3.459.635-6.772 1.787-9.833");
}

.wdoalspiw {
  fill: currentColor;
  d: path("m22.167 29.542l6.05 4.788l-2.295 7.504L32 37.221l6.078 4.613l-2.295-7.504l6.051-4.788h-7.496L32 22.167l-2.27 7.375z");
}

</style>
