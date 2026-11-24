<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnqbjiviq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-fill-sharp" /></template>
<style>
.nnqbjiviq {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414L19.586 22H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h1.586L1.293 3.707a.999.999 0 1 1 1.414-1.414M15 7a3 3 0 0 0-5.121-2.121a1 1 0 0 1-1.631-.325a1 1 0 0 1 .216-1.09A5.001 5.001 0 0 1 17 7v1h3a1 1 0 0 1 1 1v8.757L11.243 8H15Z");
}

</style>
