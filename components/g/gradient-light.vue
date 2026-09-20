<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ru9-f9nom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gradient-light" /></template>
<style>
.ru9-f9nom {
  fill: currentColor;
  d: path("M26 104a6 6 0 0 1 6-6h80a6 6 0 0 1 0 12H32a6 6 0 0 1-6-6m198-6h-80a6 6 0 0 0 0 12h80a6 6 0 0 0 0-12M72 138H32a6 6 0 0 0 0 12h40a6 6 0 0 0 0-12m152 0h-40a6 6 0 0 0 0 12h40a6 6 0 0 0 0-12m-126 6a6 6 0 0 0 6 6h48a6 6 0 0 0 0-12h-48a6 6 0 0 0-6 6m-42 34H32a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12m56 0H88a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12m56 0h-24a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12m56 0h-24a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12M32 70h192a6 6 0 0 0 0-12H32a6 6 0 0 0 0 12");
}

</style>
