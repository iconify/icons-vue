<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lald1zbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-arrow-clockwise-32-light" /></template>
<style>
.lald1zbas {
  fill: currentColor;
  d: path("M30.5 2a1 1 0 1 0-2 0v1a7.5 7.5 0 1 0 3 6a1 1 0 1 0-2 0a5.5 5.5 0 1 1-2.337-4.5H26a1 1 0 1 0 0 2h3.5a1 1 0 0 0 1-1zM30 22.5v-6.792q-.472.422-1 .776V22.5a3.5 3.5 0 0 1-3.5 3.5h-19A3.5 3.5 0 0 1 3 22.5V11.35l12.757 7.087a.5.5 0 0 0 .486 0l3.11-1.728a9 9 0 0 1-.917-.634L16 17.428L3 10.206V9.5A3.5 3.5 0 0 1 6.5 6h9.012q.182-.515.423-1H6.5A4.5 4.5 0 0 0 2 9.5v13A4.5 4.5 0 0 0 6.5 27h19a4.5 4.5 0 0 0 4.5-4.5");
}

</style>
