<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5rx-6bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bar-chart-off-outline" /></template>
<style>
.f5rx-6bgm {
  fill: currentColor;
  d: path("M4 20V9h4v11zm6 0V10l4 4v6zm4-8.85l-4-4V4h4zm6 6l-4-4V13h4zm-.225 5.475l-18.4-18.4L2.8 2.8l18.4 18.4z");
}

</style>
