<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c72j2ubuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-list-off" /></template>
<style>
.c72j2ubuy {
  fill: currentColor;
  d: path("M19.833 21.26L2.74 4.167l.713-.713l17.092 17.092zm-4.508-8.76l-1-1h2.848v1zm-4.5-4.5l-1-1H20v1zm-.267 9v-1h2.865v1zm-3.75-4.5v-1h4.265v1zM4 8V7h2.573v1z");
}

</style>
