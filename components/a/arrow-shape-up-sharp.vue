<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hij7phbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-sharp" /></template>
<style>
.hij7phbrp {
  fill: currentColor;
  d: path("M8.539 20v-5.808H4L12 5l8 9.192h-4.538V20z");
}

</style>
