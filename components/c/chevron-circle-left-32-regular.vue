<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7rw9sb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-left-32-regular" /></template>
<style>
.o7rw9sb_a {
  fill: currentColor;
  d: path("M17.293 22.707a1 1 0 0 0 1.414-1.414L13.414 16l5.293-5.293a1 1 0 0 0-1.414-1.414l-5.879 5.878l-.028.033l-.073.08a1 1 0 0 0-.293.716c-.003.26.097.484.293.718c.041.05.05.06.1.11h.002zM16 30c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14m12-14c0 6.627-5.373 12-12 12S4 22.627 4 16S9.373 4 16 4s12 5.373 12 12");
}

</style>
