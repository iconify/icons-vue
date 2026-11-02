<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajkkdk00a"/><path class="mp99cub2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duotone-round" /></template>
<style>
.ajkkdk00a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 2c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-3 3a2.414 2.414 0 0 1-3.414 0l-3-3a1.36 1.36 0 0 1-.382-1.186C7.072 2.572 8.102 2 9 2Zm0 20H9c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.311.31.456.752.382 1.186C16.928 21.428 15.898 22 15 22");
}

.ft5dv1b6b {
  fill: none;
}

.mp99cub2r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3H9c-.738 0-1.369.631-1 1l3 3a1.414 1.414 0 0 0 2 0l3-3c.369-.369-.262-1-1-1zm-7 9h2m4 0h2m4 0h2m-7 9H9c-.738 0-1.369-.631-1-1l3-3a1.414 1.414 0 0 1 2 0l3 3c.369.369-.262 1-1 1z");
}

</style>
