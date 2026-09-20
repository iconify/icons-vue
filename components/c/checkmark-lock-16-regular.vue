<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_8r1nb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-lock-16-regular" /></template>
<style>
.e_8r1nb6b {
  fill: currentColor;
  d: path("M1 7a6 6 0 0 1 11.922-.97a3 3 0 0 1 1.051.356A7 7 0 1 0 8 13.93v-1.012Q7.511 13 7 13a6 6 0 0 1-6-6m8.854-1.146a.5.5 0 0 0-.708-.708L6.25 8.043L4.854 6.646a.5.5 0 1 0-.708.708l1.75 1.75a.5.5 0 0 0 .708 0zM10.5 9v1H10a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-.5V9a2 2 0 1 0-4 0m1 1V9a1 1 0 1 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
