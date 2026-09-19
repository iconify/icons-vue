<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bf3arzpdh"/><path class="vwtdx5b3x"/><path class="sthkw9bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-congo-brazzaville" /></template>
<style>
.bf3arzpdh {
  fill: var(--svg-color--c32129, #c32129);
  d: path("M64 21v22c0 6.075-3.373 11-10 11H21.045l39.908-41.35c2.02 2.02 3.047 5 3.047 8.346");
}

.sthkw9bns {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M59.08 11.237C57.68 10.451 55.99 10 54 10H43.272L3.202 51.509a8.6 8.6 0 0 0 1.833 1.315C6.413 53.57 8.065 54 9.998 54h11.045l39.908-41.35a8.6 8.6 0 0 0-1.873-1.417");
}

.vwtdx5b3x {
  fill: var(--svg-color--28ae66, #28ae66);
  d: path("M0 43V21c0-6.075 3.373-11 10-11h33.272L3.204 51.509C1.076 49.491 0 46.43 0 43");
}

</style>
