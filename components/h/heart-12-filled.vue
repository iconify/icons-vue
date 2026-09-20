<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vrp267e8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-12-filled" /></template>
<style>
.vrp267e8n {
  fill: currentColor;
  d: path("M5.656 2.737a2.394 2.394 0 0 0-3.447-.01c-.95.975-.945 2.559.01 3.537l3.53 3.623c.146.15.384.15.53 0l3.513-3.602a2.55 2.55 0 0 0-.01-3.535a2.395 2.395 0 0 0-3.45-.009l-.336.345z");
}

</style>
