<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb_wd9iyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:creators-app" /></template>
<style>
.mb_wd9iyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 7.267h-7.838l-2.286 13.104h6.151zM27.554 32.149c-2.29 1.393-4.296 1.674-7.187 1.674a8.005 8.005 0 1 1 0-16.01c2.315 0 4.619.27 7.186 1.832l.001-7.275c-3.092-1.274-5.906-1.473-8.136-1.473c-8.229 0-14.918 6.689-14.918 14.918s6.69 14.918 14.918 14.918c2.894 0 5.482-.252 8.136-1.327z");
}

</style>
