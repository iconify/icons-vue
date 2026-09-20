<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v_ocbsb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-person-16-filled" /></template>
<style>
.v_ocbsb7n {
  fill: currentColor;
  d: path("M8 2a4.5 4.5 0 0 0-3.155 7.708a.65.65 0 0 1 .18.287l.14.51A4.48 4.48 0 0 1 8 9.5c1.075 0 2.061.377 2.835 1.005l.14-.51a.65.65 0 0 1 .18-.287A4.5 4.5 0 0 0 8 2M5.573 12l-.112-.41A3.5 3.5 0 0 1 8 10.5c1 0 1.901.419 2.539 1.09l-.112.41zm.277 1c.21.595.774 1 1.414 1h1.472a1.5 1.5 0 0 0 1.414-1zM7 6.5a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-2a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
