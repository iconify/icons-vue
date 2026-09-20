<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ele2f0bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-added-outline-sharp" /></template>
<style>
.ele2f0bkk {
  fill: currentColor;
  d: path("M17.114 9L15 6.887l.689-.714l1.424 1.425l3.525-3.55l.714.714zM12 16.917L6 19.5V4h7v1H7v12.95l5-2.15l5 2.15V11h1v8.5zM7 5h6z");
}

</style>
