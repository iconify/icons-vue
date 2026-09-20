<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m983g0q5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-add-24-regular" /></template>
<style>
.m983g0q5z {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-7.498c.198-.474.34-.977.422-1.5H20a.5.5 0 0 0 .5-.5V6a.5.5 0 0 0-.5-.5H7.5v5.576A6.6 6.6 0 0 0 6 11.02V5.5H4a.5.5 0 0 0-.5.5v5.732A6.5 6.5 0 0 0 2 12.81zm10 1a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2zm4 1.5a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5V9a.5.5 0 0 1 .5-.5zM6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.501 8.503V18h2.496a.5.5 0 0 0 0-1H7v-2.5a.5.5 0 1 0-1 0V17H3.496a.5.5 0 0 0 0 1H6v2.503a.5.5 0 1 0 1 0");
}

</style>
