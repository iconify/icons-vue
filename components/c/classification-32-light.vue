<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mt_ok0lag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-32-light" /></template>
<style>
.mt_ok0lag {
  fill: currentColor;
  d: path("M25.13 2a4.87 4.87 0 0 1 2.278 9.173l-4.854 2.567l3.137 3.137a4.5 4.5 0 0 1 0 6.363l-4.073 4.075a1.5 1.5 0 0 1-2.122 0l-.733-.734l-2.469 2.47a3.25 3.25 0 0 1-4.595 0l-8.747-8.746a3.25 3.25 0 0 1 0-4.597l2.47-2.47l-.728-.727a1.5 1.5 0 0 1 0-2.121l4.073-4.074a4.5 4.5 0 0 1 6.364 0l3.125 3.125l2.57-4.85A4.87 4.87 0 0 1 25.129 2M3.66 16.415a2.25 2.25 0 0 0 0 3.183l8.746 8.746a2.25 2.25 0 0 0 3.181 0l2.469-2.47L6.128 13.945zm10.763-9.392a3.5 3.5 0 0 0-4.949 0l-4.073 4.074a.5.5 0 0 0 0 .707l14.802 14.804a.5.5 0 0 0 .707 0l4.074-4.075a3.5 3.5 0 0 0 0-4.949zM25.13 3a3.87 3.87 0 0 0-3.42 2.059l-2.713 5.122L21.815 13l5.125-2.712A3.87 3.87 0 0 0 25.13 3");
}

</style>
