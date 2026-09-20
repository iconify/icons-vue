<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l_t_oub8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hat-graduation-12-filled" /></template>
<style>
.l_t_oub8p {
  fill: currentColor;
  d: path("M5.16 2.189a1.96 1.96 0 0 1 1.68 0l4.874 2.309a.5.5 0 0 1 .008.9l-4.85 2.406a1.96 1.96 0 0 1-1.744 0L1 5.756V8a.5.5 0 0 1-1 0V4.975a.5.5 0 0 1 .286-.477zM2 7.369V9a.5.5 0 0 0 .147.354l.002.003l.023.021l.06.056q.075.07.217.187c.187.153.457.355.794.558C3.913 10.58 4.877 11 6 11s2.088-.42 2.757-.821a6.7 6.7 0 0 0 1.012-.745l.06-.056l.016-.016l.006-.006l.001-.001l.002-.001A.5.5 0 0 0 10 9V7.368L7.316 8.7a2.96 2.96 0 0 1-2.632 0z");
}

</style>
