<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_dok0sbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-how-to-vote" /></template>
<style>
.v_dok0sbz {
  fill: currentColor;
  d: path("M18 13h-.68l-2 2h1.91L19 17H5l1.78-2h2.05l-2-2H6l-3 3v4c0 1.1.89 2 1.99 2H19a2 2 0 0 0 2-2v-4zm-1-5.05l-4.95 4.95l-3.54-3.54l4.95-4.95zm-4.24-5.66L6.39 8.66a.996.996 0 0 0 0 1.41l4.95 4.95c.39.39 1.02.39 1.41 0l6.36-6.36a.996.996 0 0 0 0-1.41L14.16 2.3a.975.975 0 0 0-1.4-.01");
}

</style>
