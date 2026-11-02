<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ri77cob5h"/><path class="hkyqmji7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hkyqmji7a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H8c-.64 0-1.36.36-2 1l-2 2c-.369.369-1-.262-1-1V5c0-.811.306-1.686 1-2m6 0h9a2 2 0 0 1 2 2v9m-3 3h-6M3 2l19 19");
}

.ri77cob5h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 18c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3Z");
}

</style>
