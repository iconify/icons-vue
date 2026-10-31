<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9f2r9byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-checkmark-48-regular" /></template>
<style>
.w9f2r9byp {
  fill: currentColor;
  d: path("M21.606 5.855a3.78 3.78 0 0 1 4.788 0l13.174 10.742A3.91 3.91 0 0 1 41 19.628v19.486C41 41.26 39.287 43 37.175 43h-26.35C8.713 43 7 41.26 7 39.114V19.628a3.91 3.91 0 0 1 1.432-3.031zm3.192 2.021a1.26 1.26 0 0 0-1.596 0L10.027 18.617a1.3 1.3 0 0 0-.477 1.011v19.486c0 .715.571 1.294 1.275 1.294h26.35c.704 0 1.275-.579 1.275-1.294V19.628c0-.393-.176-.765-.477-1.01zm5.068 13.74a1.25 1.25 0 0 1 1.768 1.768l-9.25 9.25a1.25 1.25 0 0 1-1.768 0l-4.25-4.25a1.25 1.25 0 0 1 1.768-1.768l3.366 3.367z");
}

</style>
