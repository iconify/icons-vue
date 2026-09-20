<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fyb1feb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-left-28-filled" /></template>
<style>
.fyb1feb4r {
  fill: currentColor;
  d: path("M18.293 19.768a.75.75 0 0 0-.025-1.06l-4.146-3.958H25.25a.75.75 0 0 0 0-1.5H14.122l4.146-3.957a.75.75 0 0 0-1.036-1.086l-5.5 5.25a.75.75 0 0 0 0 1.085l5.5 5.25a.75.75 0 0 0 1.06-.024M2 14a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
