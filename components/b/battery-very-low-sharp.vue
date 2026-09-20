<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8p5wcbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-very-low-sharp" /></template>
<style>
.q8p5wcbsa {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h13V9H6z");
}

</style>
