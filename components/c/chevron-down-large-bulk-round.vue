<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f31cmbbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-large-bulk-round" /></template>
<style>
.f31cmbbwv {
  fill: currentColor;
  d: path("m12 13.586l5.293-5.293a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
