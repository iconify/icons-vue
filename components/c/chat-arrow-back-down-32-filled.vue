<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h1tufqbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-arrow-back-down-32-filled" /></template>
<style>
.h1tufqbfp {
  fill: currentColor;
  d: path("M2 16C2 8.268 8.268 2 16 2s14 6.268 14 14q0 .617-.052 1.22A9 9 0 1 0 17.22 29.948Q16.617 30 16 30c-2.37 0-4.603-.589-6.56-1.629l-5.529 1.572A1.5 1.5 0 0 1 2.06 28.09l1.572-5.527A13.94 13.94 0 0 1 2 16m21.5 0a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m-1.22 10.22L21.06 25h2.69A4.25 4.25 0 0 0 28 20.75v-.5a.75.75 0 0 0-1.5 0v.5a2.75 2.75 0 0 1-2.75 2.75h-2.69l1.22-1.22a.75.75 0 1 0-1.06-1.06l-2.5 2.5a.75.75 0 0 0 0 1.06l2.5 2.5a.75.75 0 1 0 1.06-1.06");
}

</style>
