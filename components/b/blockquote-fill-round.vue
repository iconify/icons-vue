<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_vw0tbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blockquote-fill-round" /></template>
<style>
.v_vw0tbqh {
  fill: currentColor;
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0m3-1h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
