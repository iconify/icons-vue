<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o4d4-6bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:highlight-accent-20-filled" /></template>
<style>
.o4d4-6bgs {
  fill: currentColor;
  d: path("M16.5 3v4a.5.5 0 0 1-.5.5H4a.5.5 0 0 1-.5-.5V3zm-10 7.5v7l6.447-3.106a1 1 0 0 0 .553-.894v-3z");
}

</style>
