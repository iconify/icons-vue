<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bkhk6mbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-32-filled" /></template>
<style>
.bkhk6mbuk {
  fill: currentColor;
  d: path("M16 3c7.18 0 13 5.82 13 13a1.25 1.25 0 1 1-2.5 0c0-5.799-4.701-10.5-10.5-10.5S5.5 10.201 5.5 16c0 3.567 1.78 6.717 4.5 8.614V21.75a1.25 1.25 0 1 1 2.5 0v6c0 .69-.56 1.25-1.25 1.25h-6a1.25 1.25 0 1 1 0-2.5h3.089A12.98 12.98 0 0 1 3 16C3 8.82 8.82 3 16 3m0 8.5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
