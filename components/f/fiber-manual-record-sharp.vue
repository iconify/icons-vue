<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3e7v-q8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fiber-manual-record-sharp" /></template>
<style>
.c3e7v-q8o {
  fill: currentColor;
  d: path("M7.038 16.963Q5 14.925 5 12t2.038-4.962T12 5t4.963 2.038T19 12t-2.037 4.963T12 19t-4.962-2.037");
}

</style>
