<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n571ndmex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-swap-28-regular" /></template>
<style>
.n571ndmex {
  fill: currentColor;
  d: path("M17.78 2.72a.75.75 0 1 0-1.06 1.06l3.72 3.72H5.75a.75.75 0 0 0 0 1.5h14.69l-3.72 3.72a.75.75 0 1 0 1.06 1.06l5-5a.75.75 0 0 0 0-1.06zm-6.5 12.56a.75.75 0 1 0-1.06-1.06l-5 5a.75.75 0 0 0 0 1.06l5 5a.75.75 0 1 0 1.06-1.06L7.56 20.5h14.69a.75.75 0 0 0 0-1.5H7.56z");
}

</style>
