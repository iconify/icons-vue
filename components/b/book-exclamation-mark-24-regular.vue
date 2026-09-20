<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnugvn97k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-exclamation-mark-24-regular" /></template>
<style>
.jnugvn97k {
  fill: currentColor;
  d: path("M13.25 14.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0M11.5 6.75v5a.75.75 0 0 0 1.5 0v-5a.75.75 0 0 0-1.5 0M4 4.5A2.5 2.5 0 0 1 6.5 2H18a2.5 2.5 0 0 1 2.5 2.5v14.25a.75.75 0 0 1-.75.75H5.5a1 1 0 0 0 1 1h13.25a.75.75 0 0 1 0 1.5H6.5A2.5 2.5 0 0 1 4 19.5zM19 18V4.5a1 1 0 0 0-1-1H6.5a1 1 0 0 0-1 1V18z");
}

</style>
