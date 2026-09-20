<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pde7f8ndq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-48-filled" /></template>
<style>
.pde7f8ndq {
  fill: currentColor;
  d: path("M24 4c11.046 0 20 8.954 20 20s-8.954 20-20 20c-3.45 0-6.698-.874-9.533-2.414L6.23 43.928c-1.318.374-2.536-.844-2.16-2.162l2.341-8.238A19.9 19.9 0 0 1 4 24C4 12.954 12.954 4 24 4m8.633 13.62a1.25 1.25 0 0 0-1.768 0L20.752 27.73l-3.618-3.616a1.25 1.25 0 0 0-1.768 1.768l4.503 4.5a1.25 1.25 0 0 0 1.768 0l10.996-10.996a1.25 1.25 0 0 0 0-1.768");
}

</style>
