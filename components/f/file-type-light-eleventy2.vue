<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w9mu7ib4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-eleventy2" /></template>
<style>
.w9mu7ib4t {
  fill: var(--svg-color--0d0303, #0d0303);
  d: path("M13.9 5.19v21.598H8.092V12.636q-1.41 1.1-2.727 1.782q-1.318.68-3.306 1.303v-4.838q2.932-.97 4.553-2.332t2.537-3.36zm16.041.02v21.6h-5.807V12.657q-1.41 1.1-2.728 1.782q-1.318.68-3.306 1.303v-4.837q2.932-.97 4.554-2.331q1.62-1.362 2.537-3.362z");
}

</style>
