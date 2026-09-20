<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkk348bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-music-sharp" /></template>
<style>
.jkk348bzu {
  fill: currentColor;
  d: path("M12.5 15q1.05 0 1.775-.725T15 12.5V7h3V5h-4v5.5q-.325-.25-.7-.375T12.5 10q-1.05 0-1.775.725T10 12.5t.725 1.775T12.5 15M6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
