<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e2-ieelhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-20-filled" /></template>
<style>
.e2-ieelhu {
  fill: currentColor;
  d: path("M12 16a2 2 0 1 1-4 0a2 2 0 0 1 4 0M10 2a.5.5 0 0 1 .5.5v7.793l3.146-3.147a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 1 1 .708-.708L9.5 10.293V2.5A.5.5 0 0 1 10 2");
}

</style>
