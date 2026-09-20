<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaokdcc3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-flex-start" /></template>
<style>
.gaokdcc3i {
  fill: currentColor;
  d: path("M2 4V2h20v2zm8.5 16V6h3v14z");
}

</style>
