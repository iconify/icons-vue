<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0xc7c3zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:local-pharmacy" /></template>
<style>
.v0xc7c3zj {
  fill: currentColor;
  d: path("M21 5h-2.64l1.14-3.14L17.15 1l-1.46 4H3v2l2 6l-2 6v2h18v-2l-2-6l2-6zm-5 9h-3v3h-2v-3H8v-2h3V9h2v3h3z");
}

</style>
