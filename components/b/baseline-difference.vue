<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_i_8fsih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-difference" /></template>
<style>
.r_i_8fsih {
  fill: currentColor;
  d: path("M18 23H4c-1.1 0-2-.9-2-2V7h2v14h14zM15 1H8c-1.1 0-1.99.9-1.99 2L6 17c0 1.1.89 2 1.99 2H19c1.1 0 2-.9 2-2V7zm1.5 14h-6v-2h6zm0-6h-2v2h-2V9h-2V7h2V5h2v2h2z");
}

</style>
