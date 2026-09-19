<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwzwy1bba"/><path class="axj2oqj1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-folder-copy" /></template>
<style>
.axj2oqj1c {
  fill: currentColor;
  d: path("M21 4h-7l-2-2H7c-1.1 0-1.99.9-1.99 2L5 15c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2");
}

.hwzwy1bba {
  fill: currentColor;
  d: path("M3 6H1v13c0 1.1.9 2 2 2h17v-2H3z");
}

</style>
