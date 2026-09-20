<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob-yklnhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:emergency-outline" /></template>
<style>
.ob-yklnhb {
  fill: currentColor;
  d: path("M10.25 21v-5.95L5.1 18.025L3.35 15l5.15-3l-5.15-2.975L5.1 6l5.15 2.975V3h3.5v5.975L18.9 6l1.75 3.025L15.5 12l5.15 3l-1.75 3.025l-5.15-2.975V21z");
}

</style>
