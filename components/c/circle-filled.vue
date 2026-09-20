<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-0e6zbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:circle-filled" /></template>
<style>
.n-0e6zbvg {
  fill: currentColor;
  d: path("M16.5 10a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0");
}

</style>
