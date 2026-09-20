<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1k4r5sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:exclamation-outline" /></template>
<style>
.bf1k4r5sc {
  fill: currentColor;
  d: path("M11 14V5h2v9zm0 5v-2h2v2z");
}

</style>
