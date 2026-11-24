<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="byror8e2s"/><path class="lcfsbhbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-settings-corner-bulk" /></template>
<style>
.byror8e2s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 10H11a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lcfsbhbtb {
  d: path("M16.999 15a2 2 0 0 0-1.748 1.028a2.01 2.01 0 0 0 .032 2A2 2 0 1 0 17.001 15ZM18 13.126c.707.182 1.344.55 1.854 1.071l.11-.063a1 1 0 0 1 1 1.732l-.109.063a4.04 4.04 0 0 1 0 2.142l.109.063a1 1 0 0 1-1 1.732l-.11-.063c-.511.52-1.147.89-1.854 1.071V21a1 1 0 0 1-2 0v-.126a3.97 3.97 0 0 1-1.854-1.071l-.11.063a1 1 0 0 1-1-1.732l.109-.063a4.04 4.04 0 0 1 0-2.142l-.109-.063a1 1 0 0 1 1-1.732l.11.063A4 4 0 0 1 16 13.126V13a1 1 0 0 1 2 0Z");
}

</style>
