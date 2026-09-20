<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cdm0-8bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-swap-20-filled" /></template>
<style>
.cdm0-8bwn {
  fill: currentColor;
  d: path("M12.78 3.22a.75.75 0 1 0-1.06 1.06L13.44 6H4.75a.75.75 0 0 0 0 1.5h8.69l-1.72 1.72a.75.75 0 1 0 1.06 1.06l3-3a.75.75 0 0 0 0-1.06zm-4.5 7.56a.75.75 0 1 0-1.06-1.06l-3 3a.75.75 0 0 0 0 1.06l3 3a.75.75 0 0 0 1.06-1.06L6.56 14h8.69a.75.75 0 0 0 0-1.5H6.56z");
}

</style>
