<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scghyeb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:amp-stories" /></template>
<style>
.scghyeb3q {
  fill: currentColor;
  d: path("M7 20V4h10v16zm-4-2V6h2v12zm16 0V6h2v12z");
}

</style>
