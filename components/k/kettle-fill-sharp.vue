<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh82x9bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-fill-sharp" /></template>
<style>
.xh82x9bqw {
  fill: currentColor;
  d: path("M4 2h12a1 1 0 0 1 1 1v3h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-3v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V6.414L3.293 3.707A1 1 0 0 1 4 2m13 10h2V8h-2Zm1 8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
