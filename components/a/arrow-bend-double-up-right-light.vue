<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="arhl4cbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-double-up-right-light" /></template>
<style>
.arhl4cbtq {
  fill: currentColor;
  d: path("m228.24 108.24l-48 48a6 6 0 0 1-8.48-8.48L215.51 104l-43.75-43.76a6 6 0 0 1 8.48-8.48l48 48a6 6 0 0 1 0 8.48m-48-8.48l-48-48a6 6 0 1 0-8.48 8.48L161.51 98H128A102.12 102.12 0 0 0 26 200a6 6 0 0 0 12 0a90.1 90.1 0 0 1 90-90h33.51l-37.75 37.76a6 6 0 1 0 8.48 8.48l48-48a6 6 0 0 0 0-8.48");
}

</style>
