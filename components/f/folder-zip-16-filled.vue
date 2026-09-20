<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sk2sgb8cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-zip-16-filled" /></template>
<style>
.sk2sgb8cm {
  fill: currentColor;
  d: path("M11 11a1 1 0 0 1 1 1v2.75a.25.25 0 0 1-.25.25h-1.5a.25.25 0 0 1-.25-.25V12l.005-.102A1 1 0 0 1 11 11m1.5-7A2.5 2.5 0 0 1 15 6.5v5a2.5 2.5 0 0 1-2 2.45V12a2 2 0 1 0-4 0v2H3.5A2.5 2.5 0 0 1 1 11.5V7h4.586a1.5 1.5 0 0 0 1.06-.44L9.207 4zM11 10h1.5a.5.5 0 0 0 0-1H11zM9.5 8a.5.5 0 0 0 0 1H11V8zM11 8h1.5a.5.5 0 0 0 0-1H11zM9.5 6a.5.5 0 0 0 0 1H11V6zM5.586 2a1.5 1.5 0 0 1 1.06.44L8 3.792l-2.06 2.06A.5.5 0 0 1 5.585 6H1V4.5A2.5 2.5 0 0 1 3.5 2z");
}

</style>
