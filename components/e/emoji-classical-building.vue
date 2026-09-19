<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="riwc11bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-classical-building" /></template>
<style>
.riwc11bre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.004 5.549l-13.101 7.514h26.202zM5.5 39.374h37v3.077h-37zM7.188 13.07h33.64v3.083H7.188zm.84 23.121h31.96v3.077H8.028zm2.374-20.038h3.312V36.19h-3.312zm6.936 0h3.312V36.19h-3.312zm16.954 0h3.313V36.19h-3.313zm-6.936 0h3.313V36.19h-3.313z");
}

</style>
