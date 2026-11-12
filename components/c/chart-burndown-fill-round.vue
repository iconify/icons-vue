<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6h12wbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-burndown-fill-round" /></template>
<style>
.h6h12wbdr {
  fill: currentColor;
  d: path("M4 4v12a3 3 0 0 0 3 3h12.382l-2.276-4.553c-.216-.431-.47-.857-.813-1.2c-.093-.093-.2-.197-.324-.247H14a1 1 0 0 1-.857-.486L10.434 8H7a1 1 0 0 1 0-2h4c.351 0 .677.184.857.486L14.566 11H16c1.348.001 2.357 1.478 2.894 2.553l3 6A1 1 0 0 1 21 21H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0");
}

</style>
