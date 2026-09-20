<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ys0ab6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cottage-sharp" /></template>
<style>
.k9ys0ab6a {
  fill: currentColor;
  d: path("M4 21v-9.375L2.2 13L1 11.4l3-2.3V6h2v1.575L12 3l11 8.4l-1.2 1.575l-1.8-1.35V21h-7v-6h-2v6zM4 5q0-1.25.875-2.125T7 2q.425 0 .713-.288T8 1h2q0 1.25-.875 2.125T7 4q-.425 0-.712.288T6 5z");
}

</style>
