<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-ezub9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:iot-24-filled" /></template>
<style>
.f0-ezub9j {
  fill: currentColor;
  d: path("M19 4.492a2.5 2.5 0 0 1-3.012 2.448l-1.28 2.117A4 4 0 0 1 16 12.001v.058l1.296.26a2.5 2.5 0 1 1-.279 1.475l-1.32-.266a4 4 0 0 1-1.742 1.963l.495 1.512h.05a2.5 2.5 0 1 1-1.472.479l-.496-1.516a4 4 0 0 1-3.752-1.592l-1.795.847q.015.138.015.28a2.5 2.5 0 1 1-.623-1.652l1.754-.829a4 4 0 0 1 .784-3.566l-.991-1.13a2.5 2.5 0 1 1 1.164-.948l.983 1.12A4 4 0 0 1 12 8.001c.505 0 .99.093 1.434.265l1.245-2.06A2.5 2.5 0 1 1 19 4.493");
}

</style>
