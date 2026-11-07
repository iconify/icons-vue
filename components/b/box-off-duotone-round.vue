<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zm65xry8h"/><path class="vnr51-bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vnr51-bqk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4.636 5.636l-.522.258A2 2 0 0 0 3 7.687v8.626a2 2 0 0 0 1.114 1.793l7 3.457a2 2 0 0 0 1.772 0l5.139-2.538M8.423 3.766l2.691-1.329a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687v8.656M3.32 6.603l4.51 2.226M12 13v8.77m2.374-12.053l6.306-3.115M2 3l19 19");
}

.zm65xry8h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8.423 3.766l2.691-1.329a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687v8.656Zm4.463 17.797a2 2 0 0 1-1.772 0l-7-3.457A2 2 0 0 1 3 16.313V7.687a2 2 0 0 1 1.114-1.793l.522-.258l13.389 13.389Z");
}

</style>
