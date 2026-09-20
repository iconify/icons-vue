<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d66s69kcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:list-2-outline" /></template>
<style>
.d66s69kcq {
  fill: currentColor;
  d: path("M7 18v-2h10v2zm-4-5v-2h18v2zm4-5V6h10v2z");
}

</style>
