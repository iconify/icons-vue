<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqur06b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circle-double" /></template>
<style>
.uqur06b4d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M5.25 12q0-2.796 1.977-4.773T12 5.25t4.773 1.977T18.75 12t-1.977 4.773T12 18.75t-4.773-1.977T5.25 12");
}

</style>
