<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="l5lrelrdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-month-28-filled" /></template>
<style>
.l5lrelrdx {
  fill: currentColor;
  d: path("M21.75 3A3.25 3.25 0 0 1 25 6.25v15.5A3.25 3.25 0 0 1 21.75 25H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3zM8.5 15.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m5.5 0a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-5.5-6a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m5.5 0a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m5.5 0a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
