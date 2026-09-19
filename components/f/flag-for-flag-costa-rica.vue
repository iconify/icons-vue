<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cwd8uq_lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-costa-rica" /></template>
<style>
.cwd8uq_lx {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-17.755 8.366h35.511a28.16 28.16 0 0 1 7.628 9.834H6.616a28.2 28.2 0 0 1 7.629-9.834m35.511 43.267H14.244A28.16 28.16 0 0 1 6.617 43.8h50.768a28.2 28.2 0 0 1-7.629 9.833");
}

</style>
