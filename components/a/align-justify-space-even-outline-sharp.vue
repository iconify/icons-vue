<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5js5b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-space-even-outline-sharp" /></template>
<style>
.ay5js5b-p {
  fill: currentColor;
  d: path("M20 21V3h1v18zM3 21V3h1v18zm11.5-4.5v-9h2v9zm-7 0v-9h2v9z");
}

</style>
