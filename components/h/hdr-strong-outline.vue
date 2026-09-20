<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg6xkm-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hdr-strong-outline" /></template>
<style>
.vg6xkm-gn {
  fill: currentColor;
  d: path("M5.616 15q-1.238 0-2.12-.881q-.88-.881-.88-2.119t.88-2.119Q4.379 9 5.617 9t2.118.881T8.616 12t-.882 2.119T5.616 15m1.412-1.588q.588-.587.588-1.412t-.588-1.412T5.616 10t-1.413.588T3.616 12t.587 1.413T5.616 14t1.412-.587m5.818 2.13q-1.461-1.457-1.461-3.538t1.457-3.544T16.38 7q2.082 0 3.543 1.457t1.462 3.539t-1.457 3.542T16.389 17t-3.543-1.457");
}

</style>
