<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay-3nobwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-fill" /></template>
<style>
.ay-3nobwr {
  fill: currentColor;
  d: path("M8 2h8c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a2 2 0 0 1-.424-.635c-.286-.69-.163-1.561.549-1.932c.18-.093.379-.141.582-.14m-1 9a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 2h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m6-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2ZM8 22a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14Z");
}

</style>
