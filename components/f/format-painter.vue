<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8z5p40ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:format-painter" /></template>
<style>
.v8z5p40ao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 2.25h7.75q1.398 0 2.386.989q.854.853.97 2.011H19q1.75 0 1.75 1.75v4q0 1.75-1.75 1.75h-6q-.25 0-.25.25v.826q1.5.337 1.5 2.174v3.5q0 2.25-2.25 2.25T9.75 19.5V16q0-1.837 1.5-2.174V13q0-1.75 1.75-1.75h6q.25 0 .25-.25V7q0-.25-.25-.25h-1.761q-.182 3-3.364 3h-7.75q-3.375 0-3.375-3.375v-.75q0-1.398.989-2.386q.988-.989 2.386-.989");
}

</style>
