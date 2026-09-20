<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9w6j4b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-24-regular" /></template>
<style>
.f9w6j4b_j {
  fill: currentColor;
  d: path("M9.712 1.963a3.25 3.25 0 0 1 4.597 0l7.75 7.75a3.25 3.25 0 0 1 0 4.596l-7.75 7.75a3.25 3.25 0 0 1-4.597 0l-7.749-7.75a3.25 3.25 0 0 1 0-4.596zm3.536 1.06a1.75 1.75 0 0 0-2.475 0l-7.75 7.75a1.75 1.75 0 0 0 0 2.475l7.75 7.75a1.75 1.75 0 0 0 2.475 0l7.75-7.75a1.75 1.75 0 0 0 0-2.474zM14.72 8.22a.75.75 0 1 1 1.06 1.06L13.06 12l2.72 2.72a.75.75 0 0 1-1.06 1.06L12 13.06l-2.72 2.72a.75.75 0 0 1-1.06-1.06L10.94 12L8.22 9.28a.75.75 0 1 1 1.06-1.06L12 10.94z");
}

</style>
