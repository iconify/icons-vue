<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0exxcbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-hospital-sharp" /></template>
<style>
.t0exxcbao {
  fill: currentColor;
  d: path("M10.5 17h3v-3.5H17v-3h-3.5V7h-3v3.5H7v3h3.5zM3 21V3h18v18z");
}

</style>
