<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mdyxbswyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-16-filled" /></template>
<style>
.mdyxbswyp {
  fill: currentColor;
  d: path("M1 8a7 7 0 1 1 14 0A7 7 0 0 1 1 8m6.809-3.462a.5.5 0 0 0-.16.106l-.003.003l-2.5 2.5a.5.5 0 1 0 .708.707L7.5 6.207V11a.5.5 0 0 0 1 0V6.207l1.646 1.647a.5.5 0 0 0 .708-.708l-2.5-2.5l-.003-.002a.5.5 0 0 0-.542-.106");
}

</style>
