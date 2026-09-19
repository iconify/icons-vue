<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjqjf_buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-music-off" /></template>
<style>
.xjqjf_buk {
  fill: currentColor;
  d: path("M4.27 3L3 4.27l9 9v.28c-.59-.34-1.27-.55-2-.55c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4v-1.73L19.73 21L21 19.73zM14 7h4V3h-6v5.18l2 2z");
}

</style>
