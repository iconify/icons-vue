<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1cx3qbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-stick-left-outline" /></template>
<style>
.w1cx3qbdn {
  fill: currentColor;
  d: path("M17.675 12.888Q20 11.725 20 10.075t-2.325-2.812T12 6.1T6.325 7.263T4 10.075t2.325 2.813T12 14.05t5.675-1.162M17 15.35V18q0 .825-.587 1.413T15 20H9q-.825 0-1.412-.587T7 18v-2.65q-2.275-.8-3.637-2.187T2 10.075q0-2.525 2.913-4.3T12 4t7.088 1.775t2.912 4.3q0 1.7-1.362 3.088T17 15.35m-6.225-2.85H14v-.9h-2.225V7.5h-1z");
}

</style>
