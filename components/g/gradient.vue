<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nz9mlpinq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gradient" /></template>
<style>
.nz9mlpinq {
  fill: currentColor;
  d: path("M24 104a8 8 0 0 1 8-8h80a8 8 0 0 1 0 16H32a8 8 0 0 1-8-8m200-8h-80a8 8 0 0 0 0 16h80a8 8 0 0 0 0-16M72 136H32a8 8 0 0 0 0 16h40a8 8 0 0 0 0-16m152 0h-40a8 8 0 0 0 0 16h40a8 8 0 0 0 0-16m-128 8a8 8 0 0 0 8 8h48a8 8 0 0 0 0-16h-48a8 8 0 0 0-8 8m-40 32H32a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16m56 0H88a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16m56 0h-24a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16m56 0h-24a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16M32 72h192a8 8 0 0 0 0-16H32a8 8 0 0 0 0 16");
}

</style>
