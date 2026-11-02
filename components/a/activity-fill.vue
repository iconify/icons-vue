<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e57rbs40b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:activity-fill" /></template>
<style>
.e57rbs40b {
  fill: currentColor;
  d: path("M4 11c.157 0 .311-.048.451-.116c.213-.103.4-.253.566-.419c.492-.492.816-1.126 1.034-1.781l2-6a1 1 0 0 1 1.898 0L15 17.838l1.051-3.154c.317-.95.806-1.851 1.518-2.563C18.215 11.475 19.067 11 20 11h1a1 1 0 0 1 0 2h-1c-.157 0-.311.048-.451.116c-.213.103-.4.253-.566.419c-.492.492-.816 1.126-1.034 1.781l-2 6a1 1 0 0 1-1.898 0L9 6.162L7.949 9.316c-.317.95-.806 1.851-1.518 2.563C5.785 12.525 4.933 13 4 13H3a1 1 0 0 1 0-2Z");
}

</style>
