<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1t5ljbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:colorize" /></template>
<style>
.b1t5ljbge {
  fill: currentColor;
  d: path("m20.71 5.63l-2.34-2.34a.996.996 0 0 0-1.41 0l-3.12 3.12l-1.93-1.91l-1.41 1.41l1.42 1.42L3 16.25V21h4.75l8.92-8.92l1.42 1.42l1.41-1.41l-1.92-1.92l3.12-3.12c.4-.4.4-1.03.01-1.42M6.92 19L5 17.08l8.06-8.06l1.92 1.92z");
}

</style>
