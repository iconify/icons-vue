<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe6_3t3sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allergen-egg" /></template>
<style>
.qe6_3t3sr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M12 6q2.245 0 3.744 2.516Q17 10.623 17 13q0 5-5 5t-5-5q0-2.377 1.256-4.484Q9.755 6 12 6");
}

</style>
