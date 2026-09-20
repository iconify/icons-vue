<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t04a_dr2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:beaker-24-regular" /></template>
<style>
.t04a_dr2s {
  fill: currentColor;
  d: path("M8 4.5h1v6.238c0 .375-.094.744-.273 1.074l-3.584 6.603A1.75 1.75 0 0 0 6.68 21h10.638a1.75 1.75 0 0 0 1.538-2.585l-3.584-6.603A2.25 2.25 0 0 1 15 10.738V4.5h1A.75.75 0 0 0 16 3H8a.75.75 0 0 0 0 1.5m2.5 6.238V4.5h3v6.238c0 .625.156 1.24.454 1.79l.8 1.472H9.246l.8-1.473a3.75 3.75 0 0 0 .454-1.789M8.432 15.5h7.136l1.971 3.63a.25.25 0 0 1-.22.37H6.681a.25.25 0 0 1-.22-.37z");
}

</style>
