<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcggcebuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-chip-sharp" /></template>
<style>
.dcggcebuy {
  fill: currentColor;
  d: path("M8 16h8v-6h-2V8h-4v2H8zm3-6V9h2v1zm-3 9q-2.925 0-4.962-2.037T1 12t2.038-4.962T8 5h8q2.925 0 4.963 2.038T23 12t-2.037 4.963T16 19z");
}

</style>
