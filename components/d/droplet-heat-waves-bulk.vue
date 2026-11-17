<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rco467bop"/><path class="f7aqhub5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-heat-waves-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f7aqhub5o {
  d: path("M9.253 15.336c.546-.616.546-1.056 0-1.672c-.539-.606-.919-1.339-.92-2.164c.001-.825.381-1.558.92-2.164a.999.999 0 1 1 1.494 1.328c-.202.228-.413.517-.414.836c.001.319.212.608.414.836c.539.606.919 1.339.92 2.164c-.001.825-.381 1.558-.92 2.164a.999.999 0 1 1-1.494-1.328m4 0c.546-.616.546-1.056 0-1.672c-.539-.606-.919-1.339-.92-2.164c.001-.825.381-1.558.92-2.164a.999.999 0 1 1 1.494 1.328c-.202.228-.413.517-.414.836c.001.319.212.608.414.836c.539.606.919 1.339.92 2.164c-.001.825-.381 1.558-.92 2.164a.999.999 0 1 1-1.494-1.328");
}

.rco467bop {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.419 2.186a1 1 0 0 1 1.162 0c.404.289.787.607 1.164.93a25 25 0 0 1 2.508 2.475c.989 1.132 1.874 2.365 2.548 3.712c1.232 2.465 1.665 5.221.57 7.811a8 8 0 0 1-1.714 2.543A8 8 0 0 1 4 14c.001-3.174 1.714-6.085 3.747-8.409a25 25 0 0 1 2.508-2.475c.377-.323.76-.641 1.164-.93");
}

</style>
