<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="wuzmyacmq"/><path class="xs14rhobu"/><path class="bdbap1b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-32-regular" /></template>
<style>
.bdbap1b9d {
  d: path("M19 14c.39 0 .727.225.892.55A9 9 0 0 0 17.345 16H13a1 1 0 1 1 0-2z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wuzmyacmq {
  d: path("M23 30.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15M22.75 18a.75.75 0 0 0-.75.75v4.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 0-1.5H23.5v-3.75a.75.75 0 0 0-.75-.75");
}

.xs14rhobu {
  d: path("M26 3a3 3 0 0 1 3 3v2a3 3 0 0 1-1 2.236v5.28a9 9 0 0 0-2-1.002V11H6v12.5A3.5 3.5 0 0 0 9.5 27h5.438c.361.728.818 1.4 1.355 2H9.5A5.5 5.5 0 0 1 4 23.5V10.236A3 3 0 0 1 3 8V6a3 3 0 0 1 3-3zM6 5a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h20a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1z");
}

</style>
