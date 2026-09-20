<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0i-sobsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:functions-outline" /></template>
<style>
.y0i-sobsr {
  fill: currentColor;
  d: path("M7 19v-.808L13.096 12L7 5.808V5h10v1.25H9.102L14.727 12l-5.625 5.77H17V19z");
}

</style>
