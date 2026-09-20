<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xliyutb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:beenhere-outline-rounded" /></template>
<style>
.xliyutb8w {
  fill: currentColor;
  d: path("M11.375 22.4q-.3-.1-.575-.3l-6-4.5q-.375-.275-.587-.7T4 16V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v12q0 .475-.213.9t-.587.7l-6 4.5q-.275.2-.575.3t-.625.1t-.625-.1M12 20.5l6-4.5V4H6v12zm-1.05-8.35l-1.4-1.4q-.3-.3-.7-.287t-.7.287q-.3.3-.312.713t.287.712L10.25 14.3q.3.3.7.3t.7-.3l4.25-4.25q.3-.3.287-.7t-.287-.7q-.3-.3-.712-.312t-.713.287zM12 4H6h12z");
}

</style>
