<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa6-5zmcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flowchart-rounded" /></template>
<style>
.sa6-5zmcy {
  fill: currentColor;
  d: path("M15.27 19v-1.866H11.5V12.5H8.711v1.846H3V9.635h5.712V11.5H11.5V6.846h3.77V4.981H21v4.73h-5.73V7.847H12.5v8.289h2.77V14.29H21V19z");
}

</style>
