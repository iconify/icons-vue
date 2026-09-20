<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y-1vnmbeo"/><path class="b-f6v2bal"/><path class="ig72zh7vl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hashkey" /></template>
<style>
.b-f6v2bal {
  fill: var(--svg-color--0080ff, #0080ff);
  d: path("M10.128 9.572h4.744l-4.744 4.742z");
}

.ft5dv1b6b {
  fill: none;
}

.ig72zh7vl {
  fill: var(--svg-color--0072e5, #0072e5);
  d: path("M14.872 14.314h-4.744l4.744-4.742z");
}

.y-1vnmbeo {
  fill: var(--svg-color--1b2126, #1b2126);
  d: path("m8.65 4.023l-4.5-1.02a.122.122 0 0 0-.15.118v17.758c0 .076.07.135.145.118l4.502-.927a.12.12 0 0 0 .097-.118V4.138a.115.115 0 0 0-.093-.115m7.699 0l4.501-1.02a.122.122 0 0 1 .149.118v17.758a.12.12 0 0 1-.145.118l-4.502-.927a.12.12 0 0 1-.097-.118V4.138c0-.056.038-.104.093-.115");
}

</style>
