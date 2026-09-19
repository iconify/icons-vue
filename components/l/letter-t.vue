<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mowr2u5-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-t" /></template>
<style>
.mowr2u5-l {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.431 2 32s13.432 30 30 30s30-13.432 30-30C62 15.431 48.568 2 32 2m11.754 20.629h-8.682v23.878h-6.104V22.629h-8.721v-5.138h23.506z");
}

</style>
