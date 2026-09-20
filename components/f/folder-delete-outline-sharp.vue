<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-l6uobfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-delete-outline-sharp" /></template>
<style>
.r-l6uobfv {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm1-1h16V8h-8.81L9.195 6H4zm0 0V6zm9.039-1.384h4.769v-5.731h.807V10h-2.307v-.615h-1.77V10h-2.307v.885h.807zm.884-.885v-4.846h3v4.846z");
}

</style>
