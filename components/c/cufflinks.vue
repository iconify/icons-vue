<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdca0jysx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cufflinks" /></template>
<style>
.hdca0jysx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.5q-4 0-4 4q0 3.606 3.25 3.961v3.584Q3.5 14.398 3.5 17.5Q3.5 21 7 21q1.45 0 2.475-1.025T10.5 17.5t-1.025-2.475q-.749-.749-1.725-.951v-3.613Q11 10.106 11 6.5q0-4-4-4m6 4q0-4 4-4t4 4q0 3.606-3.25 3.961v3.584q2.75.353 2.75 3.455q0 3.5-3.5 3.5t-3.5-3.5q0-3.102 2.75-3.455v-3.584Q13 10.106 13 6.5");
}

</style>
