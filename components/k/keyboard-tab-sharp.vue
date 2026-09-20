<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgpe15btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-tab-sharp" /></template>
<style>
.bgpe15btd {
  fill: currentColor;
  d: path("M20 17.5v-11h1v11zm-7.673-.212l-.713-.688l4.1-4.1H3v-1h12.694l-4.056-4.1l.689-.688L17.616 12z");
}

</style>
