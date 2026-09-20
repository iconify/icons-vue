<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7g-9bc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-horiz-050-sharp" /></template>
<style>
.a7g-9bc7l {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h7V9H6z");
}

</style>
