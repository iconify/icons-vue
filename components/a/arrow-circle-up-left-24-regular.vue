<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpwprdj3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-left-24-regular" /></template>
<style>
.vpwprdj3n {
  fill: currentColor;
  d: path("M10.51 9.5h4.74a.75.75 0 0 0 0-1.5h-6.5a.75.75 0 0 0-.75.75v6.5a.75.75 0 0 0 1.5 0v-4.639l5.222 5.172a.75.75 0 0 0 1.056-1.066zM22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2s10 4.477 10 10m-10 8.5a8.5 8.5 0 1 0 0-17a8.5 8.5 0 0 0 0 17");
}

</style>
