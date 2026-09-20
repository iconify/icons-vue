<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aj2iowbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-20-filled" /></template>
<style>
.aj2iowbux {
  fill: currentColor;
  d: path("M6.636 2.287A1 1 0 0 0 5 3.059v13.998c0 .927 1.15 1.355 1.756.655l3.524-4.073a1.5 1.5 0 0 1 1.134-.518h5.592c.938 0 1.36-1.176.636-1.772z");
}

</style>
