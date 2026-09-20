<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_d9wekgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-split-hint-24-regular" /></template>
<style>
.h_d9wekgd {
  fill: currentColor;
  d: path("M20 11.25a.75.75 0 0 1-1.5 0V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5v7.25a.75.75 0 0 1-1.5 0V4a2 2 0 0 1 2-2h6.172c.515 0 1.047.22 1.413.586l5.829 5.828A2 2 0 0 1 20 9.75zm-6.5-6.629V8a.5.5 0 0 0 .5.5h3.378zM4.75 13a.75.75 0 0 1 .75.75v2.495a.75.75 0 0 1-1.5 0V13.75a.75.75 0 0 1 .75-.75m15.25.75a.75.75 0 0 0-1.5 0v2.495a.75.75 0 0 0 1.5 0zm-10.5 7.5a.75.75 0 0 1 .75-.75h3.5a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1-.75-.75m-4-2a.75.75 0 0 0-1.5 0V20a2 2 0 0 0 2 2h1.25a.75.75 0 0 0 0-1.5H6a.5.5 0 0 1-.5-.5zm13.75-.75a.75.75 0 0 0-.75.75V20a.5.5 0 0 1-.5.5h-1.25a.75.75 0 0 0 0 1.5H18a2 2 0 0 0 2-2v-.75a.75.75 0 0 0-.75-.75");
}

</style>
