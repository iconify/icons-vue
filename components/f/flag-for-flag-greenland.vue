<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hl9jaf3oz"/><path class="tmemzsnsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-greenland" /></template>
<style>
.hl9jaf3oz {
  fill: currentColor;
  d: path("M24.133 17.25c-8.145 0-14.75 6.604-14.75 14.75h29.5c0-8.146-6.605-14.75-14.75-14.75");
}

.tmemzsnsx {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 2c15.439 0 28 12.561 28 28H38.883c0 8.145-6.604 14.75-14.75 14.75S9.383 40.145 9.383 32H4C4 16.561 16.561 4 32 4");
}

</style>
