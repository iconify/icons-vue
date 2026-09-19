<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ud0oi9t_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-czechia" /></template>
<style>
.ud0oi9t_w {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 2c15.439 0 28 12.561 28 28H33.414l-20.48 20.48a29 29 0 0 1-1.414-1.414L30.586 32L11.52 12.934C16.635 7.443 23.922 4 32 4");
}

</style>
