<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viwrbjb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:graphic-eq-outline" /></template>
<style>
.viwrbjb_p {
  fill: currentColor;
  d: path("M7.75 17.116V6.885h1v10.23zM11.5 21V3h1v18zM4 13.308v-2.616h1v2.616zm11.25 3.807V6.885h1v10.23zM19 13.308v-2.616h1v2.616z");
}

</style>
