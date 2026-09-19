<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fep9mubyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-hungary" /></template>
<style>
.fep9mubyc {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M5.787 22.166h52.426A27.9 27.9 0 0 1 60 32c0 3.459-.635 6.771-1.787 9.833H5.787A27.9 27.9 0 0 1 4 32c0-3.459.635-6.772 1.787-9.834");
}

</style>
