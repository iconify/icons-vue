<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aqxzoygro"/><path class="lcfsbhbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-settings-corner-bulk-round" /></template>
<style>
.aqxzoygro {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 10a3 3 0 0 0-3 3v4a1 1 0 0 1-1 1c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v2a1 1 0 0 1-1 1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lcfsbhbtb {
  d: path("M16.999 15a2 2 0 0 0-1.748 1.028a2.01 2.01 0 0 0 .032 2A2 2 0 1 0 17.001 15ZM18 13.126c.707.182 1.344.55 1.854 1.071l.11-.063a1 1 0 0 1 1 1.732l-.109.063a4.04 4.04 0 0 1 0 2.142l.109.063a1 1 0 0 1-1 1.732l-.11-.063c-.511.52-1.147.89-1.854 1.071V21a1 1 0 0 1-2 0v-.126a3.97 3.97 0 0 1-1.854-1.071l-.11.063a1 1 0 0 1-1-1.732l.109-.063a4.04 4.04 0 0 1 0-2.142l-.109-.063a1 1 0 0 1 1-1.732l.11.063A4 4 0 0 1 16 13.126V13a1 1 0 0 1 2 0Z");
}

</style>
