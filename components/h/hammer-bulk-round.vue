<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gi7bh9b5p"/><path class="q4nqx3z6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gi7bh9b5p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.707 20.707a3.121 3.121 0 1 1-4.414-4.414L11 8.586V8c0-1.232-.873-2.459-1.707-3.293l-1-1A1 1 0 0 1 9 2h4c1.804 0 3.47 1.056 4.707 2.293l1 1C19.422 6.008 20 6.961 20 8c0 .193.069.382.154.553c.139.277.335.522.553.74a2.41 2.41 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0c-.269-.268-.584-.513-.945-.641Z");
}

.q4nqx3z6x {
  d: path("m13.04 9.626l1.334 1.334a.999.999 0 1 1-1.414 1.414l-1.334-1.334a.999.999 0 1 1 1.414-1.414");
}

</style>
