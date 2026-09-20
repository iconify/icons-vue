<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv_x3jbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flash-on" /></template>
<style>
.bv_x3jbnr {
  fill: currentColor;
  d: path("M11 18.846V13H8.385V3h7.288L14 8.789h3.904z");
}

</style>
