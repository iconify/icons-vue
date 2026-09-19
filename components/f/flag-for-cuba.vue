<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fv_-2ubsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-cuba" /></template>
<style>
.fv_-2ubsn {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m21.678 12.3a27.9 27.9 0 0 1 5.691 11.8H26.1L14.3 14.3zM10.352 37.9l1.488-4.502l-3.932-2.873h4.917l1.476-4.426l1.519 4.426h4.873l-3.933 2.873l1.489 4.502l-3.948-2.768zm43.326 11.8H14.3l11.8-11.8h33.27a27.9 27.9 0 0 1-5.692 11.8");
}

</style>
