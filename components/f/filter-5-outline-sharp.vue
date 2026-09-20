<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af7l3e9du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-5-outline-sharp" /></template>
<style>
.af7l3e9du {
  fill: currentColor;
  d: path("M11 15h6V9h-4V7h4V5h-6v6h4v2h-4zm-5 3V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4z");
}

</style>
