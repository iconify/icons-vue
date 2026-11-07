<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao5vhdg0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-restore-fill" /></template>
<style>
.ao5vhdg0m {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 1 5.829V18a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8.829A3.001 3.001 0 0 1 5 3m1 6v9a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V9Zm5 4.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 13.414V17a1 1 0 0 1-2 0Z");
}

</style>
