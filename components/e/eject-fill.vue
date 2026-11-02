<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etx8y8h4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-fill" /></template>
<style>
.etx8y8h4i {
  fill: currentColor;
  d: path("m4.456 12.41l5-8a3 3 0 0 1 5.088 0l5 8A2.999 2.999 0 0 1 17 17H7a3 3 0 0 1-2.544-4.59M19 21H5a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2");
}

</style>
