<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sabkaqbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-32-filled" /></template>
<style>
.sabkaqbza {
  fill: currentColor;
  d: path("M5.366 20.884a1.25 1.25 0 0 0 1.768 0L16 12.018l8.866 8.866a1.25 1.25 0 0 0 1.768-1.768l-9.75-9.75a1.25 1.25 0 0 0-1.768 0l-9.75 9.75a1.25 1.25 0 0 0 0 1.768");
}

</style>
