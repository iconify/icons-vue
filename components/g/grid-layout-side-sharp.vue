<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liby2ob4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-layout-side-sharp" /></template>
<style>
.liby2ob4l {
  fill: currentColor;
  d: path("M21 21V3zM3 21h10V3H3zm18 0V3h-6v18z");
}

</style>
