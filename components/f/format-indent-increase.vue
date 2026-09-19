<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2zhojb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:format-indent-increase" /></template>
<style>
.o2zhojb-q {
  fill: currentColor;
  d: path("M3 21h18v-2H3zM3 8v8l4-4zm8 9h10v-2H11zM3 3v2h18V3zm8 6h10V7H11zm0 4h10v-2H11z");
}

</style>
