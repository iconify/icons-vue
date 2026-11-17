<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u079rb9nz"/><path class="k_8yiniej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biogas-plant-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k_8yiniej {
  d: path("M12.635 7H21a1 1 0 0 1 0 2h-6.202a7.1 7.1 0 0 1 1.185 2.818l.001.001q.016.09.016.181v5a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2h10.649a5.1 5.1 0 0 0-4.423-2.995a1 1 0 1 1 .089-1.998a7.1 7.1 0 0 1 3.32.993");
}

.u079rb9nz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.607 6.01a7.101 7.101 0 0 1 13.377 1.81Q22 7.91 22 8v8a2 2 0 0 1-2 2h-4v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-8q0-.09.016-.18a7.1 7.1 0 0 1 6.591-5.81");
}

</style>
