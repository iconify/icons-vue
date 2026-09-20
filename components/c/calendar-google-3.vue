<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1jkg3bus"/><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-3" /></template>
<style>
.n1jkg3bus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.731 24a2.257 2.257 0 0 1 2.25 2.25a2.257 2.257 0 0 1-2.25 2.25h-.9c-1.575 0-2.137-.225-2.812-.787m0-7.425c.675-.563 1.35-.788 2.812-.788h.9a2.257 2.257 0 0 1 2.25 2.25a2.257 2.257 0 0 1-2.25 2.25h-2.25");
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

</style>
