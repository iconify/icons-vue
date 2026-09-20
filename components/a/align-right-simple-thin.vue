<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g5035q1_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-right-simple-thin" /></template>
<style>
.g5035q1_l {
  fill: currentColor;
  d: path("M228 56v144a4 4 0 0 1-8 0V56a4 4 0 0 1 8 0m-32 40v64a12 12 0 0 1-12 12H32a12 12 0 0 1-12-12V96a12 12 0 0 1 12-12h152a12 12 0 0 1 12 12m-8 0a4 4 0 0 0-4-4H32a4 4 0 0 0-4 4v64a4 4 0 0 0 4 4h152a4 4 0 0 0 4-4Z");
}

</style>
