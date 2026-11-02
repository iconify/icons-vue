<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl6q8acnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-fill-sharp" /></template>
<style>
.sl6q8acnk {
  fill: currentColor;
  d: path("m12.707 2.293l8 8A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0");
}

</style>
