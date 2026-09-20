<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pakf59b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bungalow" /></template>
<style>
.pakf59b3a {
  fill: currentColor;
  d: path("M7 21v-6.2l-1.1 1.75l-1.7-1.05L12 3l7.8 12.5l-1.7 1.05L17 14.8V21h-4v-5h-2v5zm4-7h2v-2h-2z");
}

</style>
