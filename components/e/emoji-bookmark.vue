<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGwiCtPWFr" class="acuw_lbhm"/></defs><use href="#SVGwiCtPWFr" class="c-zrgpb5l"/><use href="#SVGwiCtPWFr" class="c-zrgpb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-bookmark" /></template>
<style>
.acuw_lbhm {
  fill: none;
  stroke: currentColor;
  d: path("M32.277 42.5L24 33.34l-8.277 9.16v-37h16.554z");
}

.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
