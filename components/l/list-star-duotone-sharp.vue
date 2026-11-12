<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="weoxq6l0i"/><path class="zj9f7vifa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-star-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.weoxq6l0i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8.2 5.8l2.8.4l-2 2l.4 2.4L7 9.4l-2.4 1.2l.4-2.4l-2-2l2.8-.4L7 3.4Z");
}

.zj9f7vifa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 7h6M3 15h18M3 21h14M7 3.4l1.2 2.4l2.8.4l-2 2l.4 2.4L7 9.4l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

</style>
