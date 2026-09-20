<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jhau5dp6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-contacts-20-filled" /></template>
<style>
.jhau5dp6c {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h9.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1h10a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2zm4 11c-2.143 0-3-.938-3-1.875C7 10.504 7.576 10 8.286 10h3.428c.71 0 1.286.504 1.286 1.125c0 .934-.857 1.875-3 1.875m1.5-5.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
