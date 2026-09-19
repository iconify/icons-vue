<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGnICrdc5N" class="swvy6g7bb"/><path id="SVGROuhZd6G" class="trmkaibit"/></defs><use href="#SVGnICrdc5N" class="c-zrgpb5l"/><use href="#SVGnICrdc5N" class="c-zrgpb5l"/><use href="#SVGROuhZd6G" class="c-zrgpb5l"/><path class="ni6bc8lyu"/><path class="vr9u-xb5b"/><path class="nii0i810i"/><use href="#SVGnICrdc5N" class="c-zrgpb5l"/><use href="#SVGROuhZd6G" class="c-zrgpb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-broccoli" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ni6bc8lyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.525 31.115s4.272 0 5.695-2.846");
}

.nii0i810i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.474 31.115s-4.27 0-5.695-2.846");
}

.swvy6g7bb {
  fill: none;
  stroke: currentColor;
  d: path("M17.144 31.062q-.465.053-.946.053c-4.534 0-8.215-3.657-8.215-8.168a8.15 8.15 0 0 1 3.359-6.59c.651-.476 1.07-1.192 1.267-1.975C13.893 9.278 18.538 5.5 24.064 5.5c5.61 0 10.317 3.903 11.508 9.133c.173.759.62 1.41 1.24 1.883a8.1 8.1 0 0 1 3.205 6.46c0 4.496-3.666 8.14-8.187 8.14q-.178 0-.355-.008");
}

.trmkaibit {
  fill: none;
  stroke: currentColor;
  d: path("M31.474 31.115s-.15 0-.405-.02h-.029m-13.56-.058c-.57.078-.955.078-.955.078");
}

.vr9u-xb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.04 31.094s-2.413 3.58-2.413 5.714v4.24c0 .802-.65 1.452-1.453 1.452h-5.636c-.803 0-1.453-.65-1.453-1.453v-4.24c0-2.134-2.05-5.89-2.05-5.89");
}

</style>
