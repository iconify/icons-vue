<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0gbivbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-edit-fill-round" /></template>
<style>
.n0gbivbrt {
  fill: currentColor;
  d: path("M17.45 8.276A7.001 7.001 0 1 0 11 18a1 1 0 0 1 0 2a8.9 8.9 0 0 1-3.504-.708a8.9 8.9 0 0 1-2.86-1.928a9 9 0 0 1-.002-12.726a9.01 9.01 0 0 1 9.87-1.93A8.99 8.99 0 0 1 20 11a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.55-2.724M12 7v3h2a1 1 0 0 1 0 2h-3a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0m5.707 14.707A1 1 0 0 1 17 22h-2a1 1 0 0 1-1-1v-2c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414Z");
}

</style>
