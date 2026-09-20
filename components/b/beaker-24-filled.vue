<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3_m5ccnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:beaker-24-filled" /></template>
<style>
.f3_m5ccnm {
  fill: currentColor;
  d: path("M9 4.5v6.238c0 .375-.094.744-.273 1.074L7.54 14h8.922l-1.188-2.188A2.25 2.25 0 0 1 15 10.738V4.5h1A.75.75 0 0 0 16 3H8a.75.75 0 0 0 0 1.5zm8.275 11H6.725l-1.582 2.915A1.75 1.75 0 0 0 6.68 21h10.638a1.75 1.75 0 0 0 1.538-2.585z");
}

</style>
