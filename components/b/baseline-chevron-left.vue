<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkn5vwbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-chevron-left" /></template>
<style>
.tkn5vwbtp {
  fill: currentColor;
  d: path("M15.41 7.41L14 6l-6 6l6 6l1.41-1.41L10.83 12z");
}

</style>
