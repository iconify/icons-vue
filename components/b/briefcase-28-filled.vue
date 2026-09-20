<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f8hdt4b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-28-filled" /></template>
<style>
.f8hdt4b1q {
  fill: currentColor;
  d: path("M26 21.25A3.75 3.75 0 0 1 22.25 25H5.75A3.75 3.75 0 0 1 2 21.25v-6.828A5.23 5.23 0 0 0 5.75 16h5.75v.5A1.5 1.5 0 0 0 13 18h2a1.5 1.5 0 0 0 1.5-1.5V16h5.75c1.47 0 2.797-.605 3.75-1.578zM16.25 2.5a2.25 2.25 0 0 1 2.25 2.25V7h3.75a3.75 3.75 0 0 1 0 7.5H16.5A1.5 1.5 0 0 0 15 13h-2a1.5 1.5 0 0 0-1.5 1.5H5.75a3.75 3.75 0 1 1 0-7.5H9.5V4.75a2.25 2.25 0 0 1 2.25-2.25zM11.75 4a.75.75 0 0 0-.75.75V7h6V4.75a.75.75 0 0 0-.75-.75z");
}

</style>
