<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="f0rmx8baz"/><path class="tw6astbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-up-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f0rmx8baz {
  d: path("M192 64v104L88 64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tw6astbvb {
  d: path("M192 56H88a8 8 0 0 0-5.66 13.66L128.69 116l-70.35 70.34a8 8 0 0 0 11.32 11.32L140 127.31l46.34 46.35A8 8 0 0 0 200 168V64a8 8 0 0 0-8-8m-8 92.69l-38.34-38.34L107.31 72H184Z");
}

</style>
