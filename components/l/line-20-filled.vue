<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqbqk5d-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-20-filled" /></template>
<style>
.dqbqk5d-x {
  fill: currentColor;
  d: path("M17.78 2.22a.75.75 0 0 1 0 1.06l-14.5 14.5a.75.75 0 0 1-1.06-1.06l14.5-14.5a.75.75 0 0 1 1.06 0");
}

</style>
