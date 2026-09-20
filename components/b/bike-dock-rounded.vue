<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm617nbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bike-dock-rounded" /></template>
<style>
.bm617nbfr {
  fill: currentColor;
  d: path("M3.95 21q-.425 0-.687-.325T3 19.925q0-.375.163-.687t.512-.413L7.25 17.8L8.775 4.775q.1-.75.663-1.263T10.775 3H13.2q.775 0 1.338.513t.662 1.262L16.725 17.8l3.55 1q.35.125.538.425T21 19.9q0 .45-.287.775T20 21zM11 18h2V6q0-.425-.288-.712T12 5t-.712.288T11 6z");
}

</style>
