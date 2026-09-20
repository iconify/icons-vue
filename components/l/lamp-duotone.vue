<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="nh_x8o5id"/><path class="riivapb7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lamp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nh_x8o5id {
  d: path("M240 152H16L64 40h128Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.riivapb7s {
  d: path("m247.35 148.85l-48-112A8 8 0 0 0 192 32H64a8 8 0 0 0-7.35 4.85l-48 112A8 8 0 0 0 16 160h104v48H96a8 8 0 0 0 0 16h64a8 8 0 0 0 0-16h-24v-48h56v32a8 8 0 0 0 16 0v-32h32a8 8 0 0 0 7.35-11.15M28.13 144l41.15-96h117.44l41.15 96Z");
}

</style>
