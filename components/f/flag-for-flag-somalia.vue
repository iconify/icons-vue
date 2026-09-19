<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="az9gfw40b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-somalia" /></template>
<style>
.az9gfw40b {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m9.724 44.022L32 39.097l-9.724 6.926l3.672-11.259l-9.682-6.976l11.99-.034L32 16.522l3.743 11.231l11.99.034l-9.686 6.976z");
}

</style>
