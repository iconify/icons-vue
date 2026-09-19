<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjh07bb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:handshake-student" /></template>
<style>
.fjh07bb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.2 4.5l-6.5 39h7.8l1.803-10.819l7.548-6.292L24 43.5h7.8l6.5-39h-7.8l-2.35 14.09l-7.548 6.291L24 4.5z");
}

</style>
