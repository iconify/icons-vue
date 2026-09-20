<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z54hf4bii"/><path class="hytssyb6o"/><path class="y8k9a4baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:espaol" /></template>
<style>
.hytssyb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.437 4.5v36.555h23.31a1.875 1.875 0 0 0 1.875-1.875V6.375A1.875 1.875 0 0 0 36.747 4.5Zm4.973 36.865V43.5l-1.412-.593l-1.607.593v-2.135m10.142-.023v2.135l-1.413-.593l-1.606.593v-2.135");
}

.y8k9a4baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.361 8.901H33.27V19.56H17.361zm.026 2.863h15.909m-15.909 4.962h15.909");
}

.z54hf4bii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.378 6.375V39.18a1.875 1.875 0 0 0 1.875 1.875h2.184V4.5h-2.184a1.875 1.875 0 0 0-1.875 1.875");
}

</style>
