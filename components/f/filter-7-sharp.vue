<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-31-mbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-7-sharp" /></template>
<style>
.i-31-mbsn {
  fill: currentColor;
  d: path("M11 15h2l4-8V5h-6v2h4zm-5 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
