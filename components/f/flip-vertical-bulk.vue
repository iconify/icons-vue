<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rsvi6hbdf"/><path class="jvfhggt3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jvfhggt3x {
  d: path("M7 11a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.rsvi6hbdf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a2 2 0 0 1-.424-.635c-.286-.69-.163-1.561.549-1.932c.18-.093.379-.141.582-.14m8 20H8a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14");
}

</style>
