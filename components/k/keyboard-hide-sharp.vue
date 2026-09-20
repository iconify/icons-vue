<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk4atxs9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-hide-sharp" /></template>
<style>
.mk4atxs9l {
  fill: currentColor;
  d: path("m12 23l-4-4h8zM2 17V3h20v14zm6-3h8v-2H8zm-3-3h2V9H5zm3 0h2V9H8zm3 0h2V9h-2zm3 0h2V9h-2zm3 0h2V9h-2zM5 8h2V6H5zm3 0h2V6H8zm3 0h2V6h-2zm3 0h2V6h-2zm3 0h2V6h-2z");
}

</style>
