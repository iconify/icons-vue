<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd6m6bbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-edit" /></template>
<style>
.kd6m6bbyb {
  fill: currentColor;
  d: path("M11 11V4h11v7zm-9 9v-7h10v7zm0-9V4h7v7zm12 11v-3.075l5.525-5.5q.225-.225.5-.325t.55-.1q.3 0 .575.113t.5.337l.925.925q.225.225.325.5t.1.55t-.1.563t-.325.512l-5.5 5.5zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
