<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="seypdzjxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-twelve-oclock" /></template>
<style>
.seypdzjxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.043 24.012v-10.28m-.003-5.619v2.07M2.5 24c-.004 11.87 9.62 21.496 21.493 21.5c11.875.004 21.503-9.616 21.507-21.487V24c.004-11.87-9.62-21.496-21.493-21.5C12.132 2.496 2.504 12.116 2.5 23.987z");
}

</style>
