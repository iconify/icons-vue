<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="radw3nhfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:export-fill" /></template>
<style>
.radw3nhfv {
  fill: currentColor;
  d: path("M14.293 6.707L13 5.414V15a1 1 0 0 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414M4 9v10a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1a1 1 0 0 1 0-2a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3a1 1 0 0 1 0 2a1 1 0 0 0-1 1");
}

</style>
