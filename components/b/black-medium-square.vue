<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rf31_lbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-medium-square" /></template>
<style>
.rf31_lbll {
  fill: currentColor;
  d: path("M7 8h48v48H7z");
}

</style>
