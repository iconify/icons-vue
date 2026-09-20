<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="undfsxbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-card-sharp" /></template>
<style>
.undfsxbov {
  fill: currentColor;
  d: path("M4 12h16V8H4zm15 10v-3h-3v-2h3v-3h2v3h3v2h-3v3zM2 20V4h20v8h-3q-2.075 0-3.537 1.463T14 17v3z");
}

</style>
