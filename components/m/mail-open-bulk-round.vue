<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gfmno1bit"/><path class="hfdgfobpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gfmno1bit {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 22H7a5 5 0 0 1-5-5v-6c.001-2.024 1.888-3.794 3.445-4.832l3-2a6.41 6.41 0 0 1 7.11 0l3 2C20.112 7.206 21.999 8.976 22 11v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22");
}

.hfdgfobpy {
  d: path("M8.707 13.293c.556.555 1.545.707 2.293.707h2c.748 0 1.737-.152 2.293-.707l4-4a.999.999 0 1 1 1.414 1.414l-4 4C15.748 15.665 14.317 16 13 16h-2c-1.317 0-2.748-.335-3.707-1.293l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

</style>
