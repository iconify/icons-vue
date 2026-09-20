<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu52nffnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:app-promo-sharp" /></template>
<style>
.mu52nffnb {
  fill: currentColor;
  d: path("m16 11l-4 4l-4-4l1.4-1.4l1.6 1.55V7h2v4.15l1.6-1.55zm-6 9h4v-1h-4zm-5 3V1h14v22zm2-7h10V6H7z");
}

</style>
