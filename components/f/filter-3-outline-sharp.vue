<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaw5z-ncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-3-outline-sharp" /></template>
<style>
.aaw5z-ncw {
  fill: currentColor;
  d: path("M11 15h6V5h-6v2h4v2h-2v2h2v2h-4zm-5 3V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4z");
}

</style>
