<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="me09xnb-v"/><defs><path id="SVGYaKOibDu" class="chzwp2bjo"/></defs><use href="#SVGYaKOibDu" class="n1mjunbsu"/><clipPath id="SVGmNxKUPEN"><use href="#SVGYaKOibDu"/></clipPath><g clip-path="url(#SVGmNxKUPEN)"><path class="h6eycwbkx"/></g><g clip-path="url(#SVGmNxKUPEN)"><path class="h0cgp4zjm"/></g><g clip-path="url(#SVGmNxKUPEN)" class="ehej3-bmx"><path class="rbcf3sm5h"/></g><path class="v-az4acxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:grinning-face" /></template>
<style>
.chzwp2bjo {
  d: path("M63.89 98.06c23.15.05 40.56-12.97 41.19-29.05a232.2 232.2 0 0 1-82.38 0c.63 16.08 18.04 29.1 41.19 29.05");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.h0cgp4zjm {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M92.21 108c-1.1 0-2-.9-2-2V61.07c0-1.1.9-2 2-2s2 .9 2 2V106a2 2 0 0 1-2 2");
}

.h6eycwbkx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M78.05 108c-1.1 0-2-.9-2-2V61.07c0-1.1.9-2 2-2s2 .9 2 2V106a2 2 0 0 1-2 2");
}

.me09xnb-v {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M63.89 9.64C1.58 9.64.1 79.5.1 93.33s28.56 25.03 63.79 25.03c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.rbcf3sm5h {
  d: path("M63.89 108c-1.1 0-2-.9-2-2V61.07c0-1.1.9-2 2-2s2 .9 2 2V106c0 1.1-.9 2-2 2m-14.17 0c-1.1 0-2-.9-2-2V61.07c0-1.1.9-2 2-2s2 .9 2 2V106a2 2 0 0 1-2 2m-14.16 0c-1.1 0-2-.9-2-2V61.07c0-1.1.9-2 2-2s2 .9 2 2V106a2 2 0 0 1-2 2");
}

.v-az4acxw {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M42 58.3c-4.49.04-8.17-4.27-8.22-9.62c-.05-5.37 3.55-9.75 8.04-9.79c4.48-.04 8.17 4.27 8.22 9.64c.05 5.35-3.55 9.72-8.04 9.77m44.11 0c4.48-.01 8.11-4.36 8.1-9.71c-.01-5.37-3.66-9.7-8.14-9.69c-4.49.01-8.13 4.36-8.12 9.73c.02 5.35 3.67 9.68 8.16 9.67m-22.1 42.26h-.25c-24.13 0-42.86-13.52-43.56-31.46c-.03-.76.29-1.49.86-1.98c.57-.5 1.33-.71 2.08-.57c26.82 4.84 54.67 4.84 81.5 0c.75-.14 1.51.08 2.08.57c.57.5.89 1.23.86 1.98c-.71 17.94-19.44 31.46-43.57 31.46m-.13-5h.13c19.55 0 35.56-10.1 38.2-23.52a235.8 235.8 0 0 1-76.65 0c2.64 13.42 18.65 23.52 38.2 23.52z");
}

</style>
