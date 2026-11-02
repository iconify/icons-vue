<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amhq5c_vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-2-fill" /></template>
<style>
.amhq5c_vu {
  fill: currentColor;
  d: path("M11 2h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a1 1 0 0 1 0-2a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-8a.997.997 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3m-9 9a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
