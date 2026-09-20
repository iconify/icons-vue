<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x9z4amisi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-clock-32-filled" /></template>
<style>
.x9z4amisi {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5V9H3zM3 11v13.5A4.5 4.5 0 0 0 7.5 29h8.792A9 9 0 0 1 29 16.292V11zm20 19.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15M22.75 18a.75.75 0 0 0-.75.75v4.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 0-1.5H23.5v-3.75a.75.75 0 0 0-.75-.75");
}

</style>
