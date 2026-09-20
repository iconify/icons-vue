<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="trqevwb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-left-32-filled" /></template>
<style>
.trqevwb3r {
  fill: currentColor;
  d: path("M11.46 5.78a1.25 1.25 0 0 1 1.76 1.759l-.086.095l-2.867 2.866h8.483a7.25 7.25 0 0 1 0 14.5H10a1.25 1.25 0 1 1 0-2.5h8.75a4.75 4.75 0 0 0 0-9.5h-8.482l2.866 2.866a1.25 1.25 0 0 1-1.768 1.768l-5-5a1.25 1.25 0 0 1 0-1.768l5-5z");
}

</style>
