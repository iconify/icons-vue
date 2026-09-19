<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="njcj8lbmo"/><path class="iqr8_vqzw"/><path class="bdp-4obyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:face-with-cold-sweat" /></template>
<style>
.bdp-4obyj {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M22.385 49.29c-.63.717-.241 1.918.796 1.918c1.197 0 5.495-1.813 9.757-1.813c4.771 0 9.496 1.813 9.756 1.813c1.037 0 1.418-1.201.802-1.918c-5.718-6.595-15.404-6.595-21.11 0M37.05 32.417c0 2.336 4.261-.28 8.02-.28c3.764 0 8.02 2.617 8.02.28s-4.26-4.861-8.02-4.861c-3.761 0-8.02 2.525-8.02 4.861m-24.269 0c0 2.336 4.259-.28 8.02-.28s8.02 2.617 8.02.28s-4.26-4.861-8.02-4.861s-8.02 2.525-8.02 4.861");
}

.iqr8_vqzw {
  fill: var(--svg-color--58c5e8, #58c5e8);
  d: path("M.087 16.321c0 4.704 3.136 8.516 7.01 8.516c3.875 0 7.01-3.812 7.01-8.516S10.971.016 7.097.016c-3.87 0-7.01 11.601-7.01 16.305");
}

.njcj8lbmo {
  cx: 32px;
  cy: 31.989px;
  r: 31.981px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

</style>
