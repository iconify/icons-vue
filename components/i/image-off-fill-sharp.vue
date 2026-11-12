<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvpjy2rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-fill-sharp" /></template>
<style>
.blvpjy2rq {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L20.586 22H3a1 1 0 0 1-1-1v-1.586l8-8L8.586 10L2 16.586V3.414l-.707-.707a.999.999 0 1 1 1.414-1.414M6.243 2H21a1 1 0 0 1 1 1v14.757ZM15 7a2 2 0 1 0 3.999.001A2 2 0 0 0 15 7");
}

</style>
