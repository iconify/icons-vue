<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux65vebqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-score" /></template>
<style>
.ux65vebqe {
  fill: currentColor;
  d: path("M10.125 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v6h-2.725l-4.325 4.325l-2.85-2.8l-4.225 4.225zm4.825 2l-4.25-4.25l1.4-1.4l2.85 2.8l5.65-5.65l1.4 1.45zM4 8v4h16V8z");
}

</style>
