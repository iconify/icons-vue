<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8rg3ebrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-minimize-sharp" /></template>
<style>
.t8rg3ebrj {
  fill: currentColor;
  d: path("M4 20v-2h16v2Z");
}

</style>
