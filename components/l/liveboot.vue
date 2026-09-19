<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n3oz6-biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liveboot" /></template>
<style>
.n3oz6-biu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 6.884h39m-39 34.232h39m-39-4.279h39M4.5 24h39m-39 4.279h14.838M4.5 32.558h14.838M4.5 15.442h25.365M4.5 11.163h25.365M4.5 19.721h25.365");
}

</style>
