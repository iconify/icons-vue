<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1a5n6bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-fill-sharp" /></template>
<style>
.r1a5n6bax {
  fill: currentColor;
  d: path("m6.586 6l2.707-2.707A1 1 0 0 1 10 3h4c.265 0 .52.105.707.293L17.414 6H21a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm1.729 5.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114");
}

</style>
