<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxaq4rb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-corner-fill-sharp" /></template>
<style>
.yxaq4rb3x {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-9.586l-1.707-1.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1Zm-5.221 7.842a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684m-4.072 5.279a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.676a1 1 0 0 0 .293-.203L9 12.414Zm3.282 1.878c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375l.001-.003a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 19a1 1 0 0 1 0-2Z");
}

</style>
