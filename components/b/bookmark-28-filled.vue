<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="oywfsebor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-28-filled" /></template>
<style>
.oywfsebor {
  fill: currentColor;
  d: path("M9.25 3.5A3.25 3.25 0 0 0 6 6.75v18a.75.75 0 0 0 1.203.598L14 20.19l6.797 5.157A.75.75 0 0 0 22 24.75v-18a3.25 3.25 0 0 0-3.25-3.25z");
}

</style>
