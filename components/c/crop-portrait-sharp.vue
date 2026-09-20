<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l67a8ebfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-portrait-sharp" /></template>
<style>
.l67a8ebfv {
  fill: currentColor;
  d: path("M5 21V3h14v18z");
}

</style>
