<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d6aytacat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-multiple-28-regular" /></template>
<style>
.d6aytacat {
  fill: currentColor;
  d: path("M8.401 3.5A3 3 0 0 1 11 2h6.25A5.75 5.75 0 0 1 23 7.75V20a3 3 0 0 1-1.5 2.599V7.75a4.25 4.25 0 0 0-4.25-4.25zM8 5a3 3 0 0 0-3 3v17.25a.75.75 0 0 0 1.166.624l6.334-4.223l6.334 4.223A.75.75 0 0 0 20 25.25V8a3 3 0 0 0-3-3zM6.5 8A1.5 1.5 0 0 1 8 6.5h9A1.5 1.5 0 0 1 18.5 8v15.849l-5.584-3.723a.75.75 0 0 0-.832 0L6.5 23.849z");
}

</style>
