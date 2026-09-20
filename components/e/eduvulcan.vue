<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jlyultbfy"/><path class="f4tonxbfy"/><path class="so5q-bcsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eduvulcan" /></template>
<style>
.f4tonxbfy {
  d: path("M28.036 15.379v7.535c0 2.512 2.184 4.567 4.852 4.567c2.67 0 4.853-2.055 4.853-4.567v-7.536m-.001 7.765v4.567m-18.52-5.273c-.727 1.37-2.425 2.283-4.124 2.283c-2.669 0-4.852-2.055-4.852-4.567v-2.969c0-2.512 2.184-4.567 4.852-4.567c2.67 0 4.853 2.055 4.853 4.567v1.599h-9.705");
}

.jlyultbfy {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.so5q-bcsc {
  d: path("M25.502 27.634c0-2.512-2.183-4.568-4.852-4.568s-4.852 2.056-4.852 4.568v2.968c0 2.512 2.183 4.567 4.852 4.567s4.852-2.055 4.852-4.567m0 4.796V17.129");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
