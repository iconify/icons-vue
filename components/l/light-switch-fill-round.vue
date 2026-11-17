<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x772s8l1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:light-switch-fill-round" /></template>
<style>
.x772s8l1d {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm8 1a1 1 0 0 0-1 1v2h6V9a1 1 0 0 0-1-1Zm-1 7a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-2H9Z");
}

</style>
