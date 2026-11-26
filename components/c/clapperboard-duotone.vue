<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qq_8knbgj"/><path class="hfsoz6ddp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clapperboard-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hfsoz6ddp {
  d: path("M9.977 2L12 2L12.3229 2L12.0715 2.6286L10.3229 7L7.9771 7L9.4285 3.3714ZM14.477 2L16.8229 2L16.5715 2.6286L14.8229 7L12.4771 7L13.9285 3.3714ZM18.9333 2.1094C20.6923 2.5298 22 4.1121 22 6L22 7L16.9771 7L18.4285 3.3714ZM5.8229 7L2 7L2 6C2 3.7908 3.7908 2 6 2L7.8229 2L7.5715 2.6286Z");
}

.qq_8knbgj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7908 22 2 20.2092 2 18L2 9Z");
}

</style>
