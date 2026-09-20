<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhievvbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-text-clip-outline-sharp" /></template>
<style>
.lhievvbft {
  fill: currentColor;
  d: path("M4 20V4h2v16zm14 0v-7H8v-2h10V4h2v16z");
}

</style>
