<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9l-1vbki"/><path class="jm-imrb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dawdle" /></template>
<style>
.jm-imrb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.197 18.93L44.5 23.167v10.234");
}

.s9l-1vbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.774 31.082l.87-6.367l8.836-1.611l-19.152-8.506L3.5 15.808l6.09 2.823l-1.212 8.872m26.396 3.579s-17.423 4.222-26.396-3.58");
}

</style>
