<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl5-izb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-customize" /></template>
<style>
.nl5-izb-l {
  fill: currentColor;
  d: path("M3.5 3.5h7v7h-7zm10 0h7v7h-7zm-10 10h7v7h-7zm13 0h1v3h3v1h-3v3h-1v-3h-3v-1h3z");
}

</style>
