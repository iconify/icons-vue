<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3urg-bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:floor-plan-fill" /></template>
<style>
.y3urg-bbh {
  fill: currentColor;
  d: path("M12 2v7a1 1 0 0 0 2 0V2h5a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-5v-9a1 1 0 0 0-2 0v9H5a3 3 0 0 1-3-3v-5h7a1 1 0 0 0 0-2H2V5a3 3 0 0 1 3-3Z");
}

</style>
