<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aanb0_bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-timor-leste" /></template>
<style>
.aanb0_bgm {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M19.217 33.256l-5.247.381l-.934 5.246l-2.337-5.016l-5.249.354l3.799-3.485l-2.311-5.024l4.687 2.862l3.821-3.456l-.902 5.251zM9.909 49.174L27.083 32L9.909 14.826a28.3 28.3 0 0 1 3.75-3.957L41.833 32L13.659 53.131a28.3 28.3 0 0 1-3.75-3.957");
}

</style>
