<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6o_m1bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paint-off-outline-sharp" /></template>
<style>
.d6o_m1bdo {
  fill: currentColor;
  d: path("M20 3v12.875h-1.275L16.85 14H18v-2h-3.15l-2-2H18V5h-1v4h-2V5h-1v2h-2V5H7.85l-1.6-1.6q.4-.2.838-.3T8 3zm-.225 19.625L15 17.85V22H9v-6H4V6.85L1.375 4.225L2.8 2.8l18.4 18.4zM6 14h5.15l-2-2H6zm0-4h1.15L6 8.85zm5.15 4H6zm5.7 0H18z");
}

</style>
