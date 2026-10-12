<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjkqtjbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gilli-danda-sharp" /></template>
<style>
.fjkqtjbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.53 18.72L13.97 8.28l.53-.53l.53.53l.94.94l.53.53l-.53.53L5.53 20.72l-.53.53l-.53-.53l-.94-.94l-.53-.53zM6.25 16L8 17.75m5.74-13.34l1.52-1.07l.49-.34H19l.47.37l1.31 1.01l.47.37l-.47.37l-1.31 1.01l-.47.37h-3.25l-.49-.34l-1.52-1.07l-.49-.34z");
}

</style>
