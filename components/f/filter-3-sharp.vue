<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bozf2b45m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-3-sharp" /></template>
<style>
.bozf2b45m {
  fill: currentColor;
  d: path("M11 15h6V5h-6v2h4v2h-2v2h2v2h-4zm-5 3V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
