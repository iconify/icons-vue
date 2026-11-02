<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd18994yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-fill" /></template>
<style>
.gd18994yc {
  fill: currentColor;
  d: path("M13 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
