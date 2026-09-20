<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z63fulbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-checkmark-32-light" /></template>
<style>
.z63fulbhj {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M24.5 3A4.5 4.5 0 0 1 29 7.5v8.876a9 9 0 0 0-1-.672V11H4v13.5A3.5 3.5 0 0 0 7.5 28h8.204q.304.524.672 1H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm3.03 17.22a.75.75 0 0 0-1.06 0l-4.72 4.72l-1.97-1.97a.75.75 0 1 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5.25-5.25a.75.75 0 0 0 0-1.06M7.5 4A3.5 3.5 0 0 0 4 7.5V10h24V7.5A3.5 3.5 0 0 0 24.5 4z");
}

</style>
