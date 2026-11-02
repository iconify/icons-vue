<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1b9j_3vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-large-bulk" /></template>
<style>
.x1b9j_3vc {
  fill: currentColor;
  d: path("M18 5a1 1 0 0 1 1 1v8a1 1 0 0 1-2 0V8.414L6.707 18.707a.999.999 0 1 1-1.414-1.414L15.586 7H10a1 1 0 0 1 0-2Z");
}

</style>
