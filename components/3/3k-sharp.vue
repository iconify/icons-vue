<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu824dcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3k-sharp" /></template>
<style>
.lu824dcob {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13zm-6.5 0H11V9H6.5v1.5h3v1h-2v1h2v1h-3zM3 21V3h18v18z");
}

</style>
