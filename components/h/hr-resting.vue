<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3jbr4bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hr-resting" /></template>
<style>
.h3jbr4bfe {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm2.425-9.6q-.725-.675-1.062-1.6t-.338-1.9q0-2.025 1.388-3.463T8.8 3q.9 0 1.725.325t1.475.95q.65-.625 1.475-.95T15.2 3q2.025 0 3.413 1.45T20 7.925q0 .975-.363 1.863T18.6 11.375l-5.225 5.075q-.275.275-.625.413T12 17t-.75-.137t-.625-.413z");
}

</style>
