<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miqrinbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock-to-right-sharp" /></template>
<style>
.miqrinbch {
  fill: currentColor;
  d: path("M9 19h10V5H9zm-5 1V4h16v16z");
}

</style>
