<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oooy-6f6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cog-sharp" /></template>
<style>
.oooy-6f6b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4C16.418 4 20 7.58 20 12M12 4C7.582 4 4 7.58 4 12M12 4V1M20 12C20 16.42 16.418 20 12 20M20 12H23M20 12H14M12 20C7.582 20 4 16.42 4 12M12 20V23M4 12H1M14 12C14 10.9 13.105 10 12 10C10.895 10 10 10.9 10 12C10 13.1 10.895 14 12 14C13.105 14 14 13.1 14 12ZM6.711 2.85L8 5.08L10.994 10.27M16 18.94L17.289 21.17M2.837 6.71L5.069 8M18.926 16L21.158 17.29M2.842 17.29L5.074 16M18.931 8L21.163 6.71M6.711 21.17L8 18.94L11.007 13.73M16 5.08L17.289 2.85");
}

</style>
