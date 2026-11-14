<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5lqsrbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-palm" /></template>
<style>
.a5lqsrbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V11m0 0Q7 4.5 2.75 8.5M12 11q-6-1.5-8.5 4.5M12 11q5-6.5 9.25-2.5M12 11q6-1.5 8.5 4.5M12 11q-1-4.5.5-8");
}

</style>
