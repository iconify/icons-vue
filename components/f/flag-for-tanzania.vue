<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ifo-8jb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-tanzania" /></template>
<style>
.ifo-8jb-i {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m16.072 7.093q1.724 1.215 3.245 2.667L4.798 38.62a28 28 0 0 1-.683-4.148zm11.13 16.287q.494 2.024.683 4.149L15.929 54.907a28 28 0 0 1-3.246-2.667z");
}

</style>
