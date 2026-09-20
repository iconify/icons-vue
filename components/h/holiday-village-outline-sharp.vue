<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecxymymie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:holiday-village-outline-sharp" /></template>
<style>
.ecxymymie {
  fill: currentColor;
  d: path("M2 20V10l6-6l6 6v10zm2-2h3v-3h2v3h3v-7.175l-4-4l-4 4zm3-5v-2h2v2zm9 7V9.175L10.825 4h2.825L18 8.35V20zm4 0V7.525L16.475 4H19.3L22 6.7V20zM4 18h8z");
}

</style>
