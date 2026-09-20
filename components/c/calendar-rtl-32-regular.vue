<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cvnpk8b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-32-regular" /></template>
<style>
.cvnpk8b_y {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3zM27 9H5V7.5A2.5 2.5 0 0 1 7.5 5h17A2.5 2.5 0 0 1 27 7.5zM5 11h22v13.5a2.5 2.5 0 0 1-2.5 2.5h-17A2.5 2.5 0 0 1 5 24.5zm16.5 7a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M20 21.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0M16 23a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m-1.5-6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m-4 1.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
