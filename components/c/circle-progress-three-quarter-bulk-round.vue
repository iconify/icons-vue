<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="y6jv1zb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-three-quarter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.y6jv1zb0o {
  d: path("M11 11V7a1 1 0 0 1 1-1a5.9 5.9 0 0 1 2.336.472c.713.3 1.361.737 1.907 1.285A5.98 5.98 0 0 1 18 12a5.97 5.97 0 0 1-1.757 4.243A5.98 5.98 0 0 1 12 18a5.97 5.97 0 0 1-4.243-1.757a6 6 0 0 1-1.285-1.907A5.9 5.9 0 0 1 6 12a1 1 0 0 1 1-1Zm1 2H8.125a4.002 4.002 0 0 0 7.861-.662A4.005 4.005 0 0 0 13 8.125V12a1 1 0 0 1-1 1");
}

</style>
