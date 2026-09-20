<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ep8fsx1oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:less-than-or-equal-fill" /></template>
<style>
.ep8fsx1oe {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-32 152H72a8 8 0 0 1 0-16h104a8 8 0 0 1 0 16m2.35-55.65a8 8 0 0 1-4.7 15.3l-104-32a8 8 0 0 1 0-15.3l104-32a8 8 0 0 1 4.7 15.3L99.2 104Z");
}

</style>
