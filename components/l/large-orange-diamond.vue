<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l9mrmybba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:large-orange-diamond" /></template>
<style>
.l9mrmybba {
  fill: currentColor;
  d: path("M2 32L32 2l29.999 30l-30 30z");
}

</style>
