<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4p07gb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grading" /></template>
<style>
.d4p07gb4q {
  fill: currentColor;
  d: path("M16.425 20.975L13.6 18.15l1.4-1.4l1.425 1.425L19.6 15l1.4 1.4zM3 21v-2h9v2zm0-4v-2h9v2zm0-4v-2h18v2zm0-4V7h18v2zm0-4V3h18v2z");
}

</style>
