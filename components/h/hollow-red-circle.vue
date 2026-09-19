<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w347vlndh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:hollow-red-circle" /></template>
<style>
.w347vlndh {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("M32 2C15.4 2 2 15.4 2 32s13.4 30 30 30s30-13.4 30-30S48.6 2 32 2m0 51c-11.6 0-21-9.4-21-21s9.4-21 21-21s21 9.4 21 21s-9.4 21-21 21");
}

</style>
