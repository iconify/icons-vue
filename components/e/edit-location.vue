<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akff64kud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-location" /></template>
<style>
.akff64kud {
  fill: currentColor;
  d: path("M8.5 13.5h1.45l3.9-3.925l-1.425-1.425l-3.925 3.9zm6.075-4.65l.7-.7q.125-.125.125-.262t-.125-.263l-.9-.9q-.125-.125-.263-.125t-.262.125l-.7.7zM12 22q-4.025-3.425-6.012-6.362T4 10.2q0-3.75 2.413-5.975T12 2t5.588 2.225T20 10.2q0 2.5-1.987 5.438T12 22");
}

</style>
