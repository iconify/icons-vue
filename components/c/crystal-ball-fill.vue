<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7yepgbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-fill" /></template>
<style>
.q7yepgbcd {
  fill: currentColor;
  d: path("M4.697 16a8.7 8.7 0 0 1-1.591-5.552a9.2 9.2 0 0 1 1.731-4.845A8.7 8.7 0 0 1 9.104 2.46a9.28 9.28 0 0 1 5.792 0c.868.29 1.687.718 2.42 1.266a9 9 0 0 1 3.059 4.176c.971 2.72.613 5.737-1.072 8.098Zm3.618-7.557A4 4 0 0 0 8 10c0 .55.45 1 1 1s1-.45 1-1a2.005 2.005 0 0 1 2-2c.55 0 1-.45 1-1s-.45-1-1-1a4.01 4.01 0 0 0-3.685 2.443M20 18v2c0 1.1-.9 2-2 2H6c-1.1 0-2-.9-2-2v-2Z");
}

</style>
