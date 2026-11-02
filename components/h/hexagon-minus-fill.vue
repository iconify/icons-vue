<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tenr7-bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-minus-fill" /></template>
<style>
.tenr7-bii {
  fill: currentColor;
  d: path("M21 15.764a3 3 0 0 1-1.658 2.683l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236ZM15 11H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
