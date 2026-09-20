<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whrx31b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flash-off-sharp" /></template>
<style>
.whrx31b2u {
  fill: currentColor;
  d: path("M8.385 3h7.288L14 8.789h3.904l-2.56 3.725l-6.96-6.96zM11 18.846V13H8.385V9.812L2.74 4.167l.713-.713l17.092 17.092l-.713.714l-6.217-6.218z");
}

</style>
