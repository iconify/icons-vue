<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n2cv086eq"/><path class="popaz21gp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n2cv086eq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.636 16.394L8.263 5.021a25 25 0 0 1 1.992-1.905c.377-.323.76-.641 1.164-.93a1 1 0 0 1 1.162 0c.404.289.787.607 1.164.93a25 25 0 0 1 2.508 2.475c.989 1.132 1.874 2.365 2.548 3.712c1.103 2.207 1.587 4.699.835 7.091m-1.501 2.741a8.1 8.1 0 0 1-3.021 2.236A8.002 8.002 0 0 1 4 14c.001-2.412 1.004-4.689 2.36-6.64Z");
}

.popaz21gp {
  d: path("M1.293 3.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
