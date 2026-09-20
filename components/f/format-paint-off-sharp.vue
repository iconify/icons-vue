<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdyqzuu9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paint-off-sharp" /></template>
<style>
.wdyqzuu9d {
  fill: currentColor;
  d: path("M20 3v12.875h-1.275L12.85 10H18V5h-1v4h-2V5h-1v2h-2V5H7.85l-1.6-1.6q.4-.2.838-.3T8 3zm-.225 19.625L15 17.85V22H9v-6H4V6.85L1.375 4.225L2.8 2.8l18.4 18.4zM6 10h1.15L6 8.85z");
}

</style>
