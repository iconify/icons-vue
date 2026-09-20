<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxiep-ark"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-remove-outline" /></template>
<style>
.rxiep-ark {
  fill: currentColor;
  d: path("M21 7h-6V5h6zM5 21V5q0-.825.588-1.412T7 3h6v2H7v12.95l5-2.15l5 2.15V11h2v10l-7-3zM7 5h6z");
}

</style>
