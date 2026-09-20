<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwm6gq8ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:draft-outline-sharp" /></template>
<style>
.xwm6gq8ek {
  fill: currentColor;
  d: path("M4 22V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
