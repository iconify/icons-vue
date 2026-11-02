<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joueod8nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-car-fill" /></template>
<style>
.joueod8nz {
  fill: currentColor;
  d: path("M14.01 2a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Zm-4 1a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2ZM3.757 8.03l16-4a1 1 0 0 1 .486 1.94L13 7.781V10h2a1 1 0 0 1 .724.31a8.25 8.25 0 0 1 0 11.38A1 1 0 0 1 15 22H9a1 1 0 0 1-.724-.31a8.25 8.25 0 0 1 0-11.38A1 1 0 0 1 9 10h2V8.281L4.243 9.97a1 1 0 0 1-.486-1.94M9.448 12a6.25 6.25 0 0 0-1.367 3h7.838a6.25 6.25 0 0 0-1.367-3Z");
}

</style>
