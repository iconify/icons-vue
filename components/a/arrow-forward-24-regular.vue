<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqydtdbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-forward-24-regular" /></template>
<style>
.qqydtdbxr {
  fill: currentColor;
  d: path("M14.72 6.28a.75.75 0 0 1 1.06-1.06l5 5a.75.75 0 0 1 0 1.06l-5 5a.75.75 0 1 1-1.06-1.06l3.72-3.72h-7.69a6.25 6.25 0 0 0-6.25 6.25v.5a.75.75 0 0 1-1.5 0v-.5A7.75 7.75 0 0 1 10.75 10h7.69z");
}

</style>
