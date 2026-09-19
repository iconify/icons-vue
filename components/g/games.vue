<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as1-ibgvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:games" /></template>
<style>
.as1-ibgvm {
  fill: currentColor;
  d: path("M15 7.5V2H9v5.5l3 3zM7.5 9H2v6h5.5l3-3zM9 16.5V22h6v-5.5l-3-3zM16.5 9l-3 3l3 3H22V9z");
}

</style>
