<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn89k0jav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:highlighter-size-5-outline-rounded" /></template>
<style>
.fn89k0jav {
  fill: currentColor;
  d: path("m10.596 21.904l-8.5-8.5q-.14-.14-.14-.354t.14-.354l10.6-10.6q.14-.14.351-.13q.21.009.357.155l8.5 8.475q.14.14.14.354t-.14.354l-10.6 10.6q-.14.14-.354.14t-.354-.14");
}

</style>
