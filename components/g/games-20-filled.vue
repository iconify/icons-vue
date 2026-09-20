<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ouv_e6gbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:games-20-filled" /></template>
<style>
.ouv_e6gbi {
  fill: currentColor;
  d: path("M7.5 4a5.5 5.5 0 1 0 0 11h5a5.5 5.5 0 1 0 0-11zM6 7.5a.5.5 0 0 1 1 0V9h1.5a.5.5 0 0 1 0 1H7v1.5a.5.5 0 0 1-1 0V10H4.5a.5.5 0 0 1 0-1H6zm9 .5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
