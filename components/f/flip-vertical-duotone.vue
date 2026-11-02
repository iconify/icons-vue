<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ek80ctb3d"/><path class="ake-pca5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duotone" /></template>
<style>
.ake-pca5s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3H8c-.369 0-.369.631 0 1l3 3a1.414 1.414 0 0 0 2 0l3-3c.369-.369.369-1 0-1zm-7 9h2m4 0h2m4 0h2m-7 9H8c-.369 0-.369-.631 0-1l3-3a1.414 1.414 0 0 1 2 0l3 3c.369.369.369 1 0 1z");
}

.ek80ctb3d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 2c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a2 2 0 0 1-.424-.635c-.286-.69-.163-1.561.549-1.932c.18-.093.379-.141.582-.14Zm0 20H8a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14");
}

.ft5dv1b6b {
  fill: none;
}

</style>
