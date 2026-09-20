<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bpkv2ub3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-left-20-filled" /></template>
<style>
.bpkv2ub3l {
  fill: currentColor;
  d: path("M4.472 15.447a.75.75 0 0 1-.393-1.031l2.5-5.001a.75.75 0 1 1 1.342.67L6.299 13.33l9.818-4.32L5.455 4.44a.75.75 0 0 1 .59-1.378l11.192 4.796c1.005.431 1.012 1.853.011 2.293L6.782 14.756l3.246 1.298a.75.75 0 1 1-.556 1.392z");
}

</style>
