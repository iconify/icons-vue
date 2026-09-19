<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ccw1l9bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-madagascar" /></template>
<style>
.ccw1l9bpd {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-9.834 31v25.213C11.564 54.223 4 43.98 4 32S11.564 9.777 22.166 5.787V31H60v2z");
}

</style>
