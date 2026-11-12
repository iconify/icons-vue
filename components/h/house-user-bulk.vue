<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n8tr--cfk"/><path class="gosf_ks8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gosf_ks8m {
  d: path("M9.236 9.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m-3.9 7.347A5 5 0 0 1 17 21a1 1 0 0 1-2 0a3 3 0 1 0-6 0a1 1 0 0 1-2 0a4.9 4.9 0 0 1 .393-1.946");
}

.n8tr--cfk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-7c0-1.039.578-1.992 1.293-2.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6C20.422 10.008 21 10.961 21 12v7a3 3 0 0 1-3 3");
}

</style>
