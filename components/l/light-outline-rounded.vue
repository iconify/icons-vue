<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zih3g8bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:light-outline-rounded" /></template>
<style>
.zih3g8bfb {
  fill: currentColor;
  d: path("M9.175 19.825Q8 18.65 8 17H5q-.825 0-1.412-.587T3 15q0-3.5 2.3-6.038T11 6.05V4q0-.425.288-.712T12 3t.713.288T13 4v2.05q3.4.375 5.7 2.913T21 15q0 .825-.587 1.413T19 17h-3q0 1.65-1.175 2.825T12 21t-2.825-1.175M5 15h14q0-2.9-2.05-4.95T12 8t-4.95 2.05T5 15m8.413 3.413Q14 17.825 14 17h-4q0 .825.588 1.413T12 19t1.413-.587M12 17");
}

</style>
