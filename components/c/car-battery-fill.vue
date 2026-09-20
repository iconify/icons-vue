<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yq4obtbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:car-battery-fill" /></template>
<style>
.yq4obtbqz {
  fill: currentColor;
  d: path("M224 72h-16V56a16 16 0 0 0-16-16h-32a16 16 0 0 0-16 16v16h-32V56a16 16 0 0 0-16-16H64a16 16 0 0 0-16 16v16H32a16 16 0 0 0-16 16v96a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16V88a16 16 0 0 0-16-16M64 56h32v16H64Zm40 88H72a8 8 0 0 1 0-16h32a8 8 0 0 1 0 16m80 0h-8v8a8 8 0 0 1-16 0v-8h-8a8 8 0 0 1 0-16h8v-8a8 8 0 0 1 16 0v8h8a8 8 0 0 1 0 16m8-72h-32V56h32Z");
}

</style>
