<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eutirbbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-12-filled" /></template>
<style>
.eutirbbav {
  fill: currentColor;
  d: path("M8 1a2 2 0 0 1 2 2v7.5a.5.5 0 0 1-.791.407L6 8.614l-3.209 2.293A.5.5 0 0 1 2 10.5V3a2 2 0 0 1 2-2z");
}

</style>
