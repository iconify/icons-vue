<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d5hidyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lock-small" /></template>
<style>
.j7d5hidyt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.005 11.495q-.573-.573-1.255-.882V7q0-1.875-.937-2.812Q13.875 3.25 12 3.25Q8.25 3.25 8.25 7v3.613q-.682.309-1.255.882Q5.75 12.74 5.75 14.5v2q0 1.76 1.245 3.005T10 20.75h4q1.76 0 3.005-1.245T18.25 16.5v-2q0-1.76-1.245-3.005M10 10.25q-.126 0-.25.006V7q0-2.25 2.25-2.25q1.125 0 1.688.563T14.25 7v3.256q-.124-.006-.25-.006z");
}

</style>
