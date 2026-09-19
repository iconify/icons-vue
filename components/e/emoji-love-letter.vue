<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3a_3cb4q"/><path class="vwm02ltwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-love-letter" /></template>
<style>
.i3a_3cb4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.815 35.683H7.164a1.66 1.66 0 0 1-1.664-1.66v-20.41c0-.715.582-1.296 1.3-1.296h34.367c.736 0 1.333.595 1.333 1.33v20.355c0 .928-.754 1.681-1.685 1.681M6.078 12.894l16.185 15.614m19.659-15.614L27.077 27.26");
}

.vwm02ltwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.96 22.347a3.21 3.21 0 0 0-3.211-3.211a3.2 3.2 0 0 0-2.75 1.557a3.2 3.2 0 0 0-2.748-1.557a3.21 3.21 0 0 0-3.211 3.21c0 .406.078.793.215 1.15C19.317 26.55 24 29.902 24 29.902s4.683-3.352 5.745-6.406c.137-.357.215-.744.215-1.15");
}

</style>
