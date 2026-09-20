<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="swu7bccbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-right-28-filled" /></template>
<style>
.swu7bccbf {
  fill: currentColor;
  d: path("M9.707 19.768a.75.75 0 0 1 .025-1.06l4.146-3.958H2.75a.75.75 0 0 1 0-1.5h11.128L9.732 9.293a.75.75 0 1 1 1.036-1.086l5.5 5.25a.75.75 0 0 1 0 1.085l-5.5 5.25a.75.75 0 0 1-1.06-.024M26 14a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

</style>
