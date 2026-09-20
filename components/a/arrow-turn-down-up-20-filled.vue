<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="seu368bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-down-up-20-filled" /></template>
<style>
.seu368bsh {
  fill: currentColor;
  d: path("M16.447 3.472a.75.75 0 0 0-1.031-.393l-5.001 2.5a.75.75 0 1 0 .67 1.342l3.244-1.622l-4.32 9.818L5.44 4.455a.75.75 0 0 0-1.378.59l4.796 11.192c.431 1.005 1.853 1.012 2.293.011l4.606-10.466l1.298 3.246a.75.75 0 1 0 1.392-.556z");
}

</style>
