<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1tqp6ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-sparkle-fill" /></template>
<style>
.jj1tqp6ye {
  fill: currentColor;
  d: path("m14.986 5l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L17 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L19 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 7a1 1 0 0 1 0-2M4 13.586l2.293-2.293a2.414 2.414 0 0 1 3.414 0l2 2a.414.414 0 0 0 .586 0l2-2a.999.999 0 1 1 1.414 1.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a.414.414 0 0 0-.586 0L4 16.414V18a1 1 0 0 0 1 1h16a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V4a1 1 0 0 1 2 0Z");
}

</style>
