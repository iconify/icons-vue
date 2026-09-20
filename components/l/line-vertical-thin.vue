<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cbi3x0bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:line-vertical-thin" /></template>
<style>
.cbi3x0bda {
  fill: currentColor;
  d: path("M132 24v208a4 4 0 0 1-8 0V24a4 4 0 0 1 8 0");
}

</style>
