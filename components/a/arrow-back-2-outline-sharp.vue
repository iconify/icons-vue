<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ole7zcctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-2-outline-sharp" /></template>
<style>
.ole7zcctq {
  fill: currentColor;
  d: path("M15 17.192L6.846 12L15 6.808zm-1-1.842v-6.7L8.711 12z");
}

</style>
