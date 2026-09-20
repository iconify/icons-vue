<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig34qhlao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-open-outline-sharp" /></template>
<style>
.ig34qhlao {
  fill: currentColor;
  d: path("M11 12.77q.329 0 .549-.23t.22-.54q0-.329-.22-.549t-.549-.22q-.31 0-.54.22t-.23.549q0 .31.23.54t.54.23M7 20v-1l7-.692V5.11L7.616 4.5v-1L15 4.223v14.966zm-2.539 0v-1H6V3.5h12V19h1.539v1zM7 19h10V4.5H7z");
}

</style>
