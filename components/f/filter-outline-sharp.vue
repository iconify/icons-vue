<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmv4hfbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-outline-sharp" /></template>
<style>
.dmv4hfbru {
  fill: currentColor;
  d: path("M9 14h10l-3.45-4.5l-2.3 3l-1.55-2zm-3 4V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
