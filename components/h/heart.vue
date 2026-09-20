<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oq2giydkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:heart" /></template>
<style>
.oq2giydkf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.032 5.594C4.89 5.866 4 6.696 4 8.163c0 1.967 1.676 4.094 6 6.226c4.324-2.132 6-4.26 6-6.226c0-1.467-.889-2.297-2.032-2.57c-1.218-.29-2.523.103-3.167.965a1 1 0 0 1-1.602 0c-.644-.862-1.95-1.255-3.167-.964M10 4.543c-1.25-.98-2.965-1.245-4.432-.895C3.678 4.1 2 5.621 2 8.163c0 3.326 2.88 6.016 7.571 8.24a1 1 0 0 0 .857 0C15.12 14.18 18 11.49 18 8.164c0-2.542-1.678-4.064-3.568-4.515c-1.467-.35-3.183-.084-4.432.895");
}

</style>
