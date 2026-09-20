<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i5svxcccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-month-32-light" /></template>
<style>
.i5svxcccu {
  fill: currentColor;
  d: path("M7.5 4A3.5 3.5 0 0 0 4 7.5v17A3.5 3.5 0 0 0 7.5 28h17a3.5 3.5 0 0 0 3.5-3.5v-17A3.5 3.5 0 0 0 24.5 4zM3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM9.5 14a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m8-1.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m5 1.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M11 19.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m5 1.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
