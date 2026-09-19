<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_ihqfb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-yuan" /></template>
<style>
.g_ihqfb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.654 29.924A21.499 21.499 0 1 1 45.486 24M8.287 31.807h31.478M45.5 24.03H2.502m21.715-4.238v25.59M35.65 5.936L24.216 19.792M12.429 5.879l11.788 13.913");
}

</style>
