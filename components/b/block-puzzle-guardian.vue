<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ywt6bccyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:block-puzzle-guardian" /></template>
<style>
.ywt6bccyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.333 17.833H24v12.334h12.333zM24 5.5H11.667v12.333H24zm0 12.333H11.667v12.334H24zm12.333 12.334H24V42.5h12.333z");
}

</style>
