<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r7jvqtvfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-style-20-filled" /></template>
<style>
.r7jvqtvfb {
  fill: currentColor;
  d: path("M2 4.75A.75.75 0 0 1 2.75 4h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 2 4.75m6 0A.75.75 0 0 1 8.75 4h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 8 4.75m6 0a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75m-12 5A.75.75 0 0 1 2.75 9h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.75M3.25 14a1.25 1.25 0 1 0 0 2.5h13.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
