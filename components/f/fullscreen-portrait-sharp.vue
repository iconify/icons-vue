<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y353gab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fullscreen-portrait-sharp" /></template>
<style>
.y353gab5e {
  fill: currentColor;
  d: path("M8 18h8V6H8zm12 4H4V2h16z");
}

</style>
