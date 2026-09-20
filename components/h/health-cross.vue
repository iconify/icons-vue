<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blc490buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-cross" /></template>
<style>
.blc490buo {
  fill: currentColor;
  d: path("M8.673 20v-4.673H4V8.692h4.673V4h6.635v4.692H20v6.635h-4.692V20z");
}

</style>
