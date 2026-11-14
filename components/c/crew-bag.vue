<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-af7h86o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crew-bag" /></template>
<style>
.w-af7h86o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.271 8.822q.475-.072.979-.072h1V8.5q0-2.25 2.25-2.25h1q.932 0 1.591.659T14.75 8.5v.25h1q.504 0 .979.072Q16.433 4.25 12 4.25T7.271 8.822m10.976.452q.948.436 1.746 1.233q1.757 1.758 1.757 4.243v.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 17.735 2.25 15.25v-.5q0-2.485 1.757-4.243q.798-.797 1.746-1.233q.067-2.993 1.944-4.812Q9.462 2.75 12 2.75t4.303 1.712q1.877 1.819 1.944 4.812M10.75 8.75V8.5q0-.75.75-.75h1q.75 0 .75.75v.25z");
}

</style>
