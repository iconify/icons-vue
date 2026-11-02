<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiejd59ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-fill" /></template>
<style>
.yiejd59ka {
  fill: currentColor;
  d: path("M2.989 4.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L5 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177L9.014 5a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L7 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L2.986 7a1 1 0 0 1 0-2ZM10 9.586l4.293-4.293a2.414 2.414 0 0 1 3.414 0l3 3a2.414 2.414 0 0 1 0 3.414L16.414 16Zm-5.707 9.121a2.414 2.414 0 0 1 0-3.414L8.586 11L15 17.414L13.414 19H21a1 1 0 0 1 0 2H7a1 1 0 0 1-.707-.293Z");
}

</style>
