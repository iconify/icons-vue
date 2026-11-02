<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nonu48a3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-fill-round" /></template>
<style>
.nonu48a3p {
  fill: currentColor;
  d: path("m12 10.586l5.293-5.293a.999.999 0 1 1 1.414 1.414L13.414 12l5.293 5.293a.999.999 0 1 1-1.414 1.414L12 13.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L10.586 12L5.293 6.707a.999.999 0 1 1 1.414-1.414Z");
}

</style>
