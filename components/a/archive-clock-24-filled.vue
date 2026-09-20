<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b29d_bddw"/><path class="tia5nvq9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-24-filled" /></template>
<style>
.b29d_bddw {
  d: path("M23 17.5a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0M17.5 14a.5.5 0 0 1 .5.5V17h2a.5.5 0 0 1 0 1h-2.5a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tia5nvq9f {
  d: path("M20 11.498A6.5 6.5 0 0 0 17.5 11a6.5 6.5 0 0 0-3.001.733a.75.75 0 0 0-.749-.733h-3.5a.75.75 0 0 0 0 1.5h3.098a6.49 6.49 0 0 0-2.348 5c0 1.29.377 2.49 1.024 3.5H7.75A3.75 3.75 0 0 1 4 17.25V9h16zM19.5 3A1.5 1.5 0 0 1 21 4.5V6a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 6V4.5A1.5 1.5 0 0 1 4.5 3z");
}

</style>
