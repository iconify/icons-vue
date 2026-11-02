<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzy_71b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-fill-sharp" /></template>
<style>
.lzy_71b7q {
  fill: currentColor;
  d: path("M13 5.733V8h6a1 1 0 0 1 1 1v5h1a1 1 0 0 1 0 2h-1v5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-5H3a1 1 0 0 1 0-2h1V9a1 1 0 0 1 1-1h6V5.733a2.001 2.001 0 1 1 2 0m-4.011 8.266L8.986 14a1 1 0 0 0 0 2l.003.001c.134.028.261.107.375.177a4.9 4.9 0 0 1 1.458 1.458c.07.114.149.241.177.375l.001.003a1 1 0 0 0 2 0l.001-.003c.028-.134.107-.261.177-.375a4.9 4.9 0 0 1 1.458-1.458c.114-.07.241-.149.375-.177l.003-.001a1 1 0 0 0 0-2l-.003-.001c-.134-.028-.261-.107-.375-.177a4.9 4.9 0 0 1-1.458-1.458c-.07-.114-.149-.241-.177-.375L13 11.986a1 1 0 0 0-2 0l-.001.003c-.028.134-.107.261-.177.375a4.9 4.9 0 0 1-1.458 1.458c-.114.07-.241.149-.375.177");
}

</style>
