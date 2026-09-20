<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi737mzxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-8-sharp" /></template>
<style>
.yi737mzxi {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2zm10-12l-1 1v4h6v-4l-1-1l1-1V5h-6v4zm3-3v2h-2V7zm0 4v2h-2v-2z");
}

</style>
