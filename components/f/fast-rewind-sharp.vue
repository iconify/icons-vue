<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t683rry-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fast-rewind-sharp" /></template>
<style>
.t683rry-g {
  fill: currentColor;
  d: path("M19.904 16.616L12.98 12l6.923-4.615zm-8.885 0L4.096 12l6.923-4.615z");
}

</style>
