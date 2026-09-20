<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vggm8t0us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-32-regular" /></template>
<style>
.vggm8t0us {
  fill: currentColor;
  d: path("M14.707 9.293a1 1 0 1 0-1.414 1.414L18.586 16l-5.293 5.293a1 1 0 0 0 1.414 1.414l5.879-5.878l.028-.033q.035-.04.073-.08A1 1 0 0 0 20.98 16c.003-.26-.097-.484-.293-.718a1 1 0 0 0-.1-.11h-.002zM16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2M4 16C4 9.373 9.373 4 16 4s12 5.373 12 12s-5.373 12-12 12S4 22.627 4 16");
}

</style>
