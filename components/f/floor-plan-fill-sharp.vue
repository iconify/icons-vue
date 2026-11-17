<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfqex5thx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:floor-plan-fill-sharp" /></template>
<style>
.jfqex5thx {
  fill: currentColor;
  d: path("M12 2v7a1 1 0 0 0 2 0V2h7a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-7v-9a1 1 0 0 0-2 0v9H3a1 1 0 0 1-1-1v-7h7a1 1 0 0 0 0-2H2V3a1 1 0 0 1 1-1Z");
}

</style>
