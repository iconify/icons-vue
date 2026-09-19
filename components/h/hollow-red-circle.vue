<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cyhlalmup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:hollow-red-circle" /></template>
<style>
.cyhlalmup {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 51c-11.598 0-21-9.402-21-21s9.402-21 21-21s21 9.402 21 21s-9.401 21-21 21");
}

</style>
