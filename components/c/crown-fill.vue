<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p666tacei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-fill" /></template>
<style>
.p666tacei {
  fill: currentColor;
  d: path("m12.832 3.445l3.395 5.093l4.148-3.319a1.002 1.002 0 0 1 1.609.96l-1.702 9.358A3 3 0 0 1 17.331 18H6.669a3 3 0 0 1-2.951-2.463L2.016 6.179a1.001 1.001 0 0 1 1.609-.96l4.148 3.319l3.395-5.093a1 1 0 0 1 1.664 0M19 20a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
