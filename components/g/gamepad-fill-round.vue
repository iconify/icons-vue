<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tza3o2b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gamepad-fill-round" /></template>
<style>
.tza3o2b_b {
  fill: currentColor;
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Zm9 0a1 1 0 0 0-2 0v2H7a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2h-2Zm7 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-1.99 4H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
