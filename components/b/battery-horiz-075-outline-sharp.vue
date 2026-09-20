<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oatzu2k0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-horiz-075-outline-sharp" /></template>
<style>
.oatzu2k0q {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h4V9H6z");
}

</style>
