<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6_3desfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:insert-text-outline" /></template>
<style>
.h6_3desfp {
  fill: currentColor;
  d: path("M11 16v-6H8V8h8v2h-3v6zM1 23v-6h2V7H1V1h6v2h10V1h6v6h-2v10h2v6h-6v-2H7v2zm6-4h10v-2h2V7h-2V5H7v2H5v10h2zM3 5h2V3H3zm16 0h2V3h-2zm0 16h2v-2h-2zM3 21h2v-2H3zm2-2");
}

</style>
