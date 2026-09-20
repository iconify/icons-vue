<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nf6qerb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dot-bold" /></template>
<style>
.nf6qerb1f {
  fill: currentColor;
  d: path("M144 128a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
