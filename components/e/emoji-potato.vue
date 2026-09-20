<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGJwwVBgKr" class="xvektccux"/></defs><use href="#SVGJwwVBgKr" class="c-zrgpb5l"/><use href="#SVGJwwVBgKr" class="c-zrgpb5l"/><path class="dulx6qbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-potato" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dulx6qbit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.612 10.094a.863.863 0 0 0 1.727.001a.863.863 0 0 0-1.727-.002zm-2.221 24.274a2.22 2.22 0 0 0 4.441.004v-.004a2.22 2.22 0 0 0-4.44-.004z");
}

.xvektccux {
  fill: none;
  stroke: currentColor;
  d: path("M39.84 18.08c0 12.53-5.204 18.639-10.054 21.607c-4.237 2.606-8.215 2.813-8.215 2.813c-7.405 0-13.411-6.006-13.411-13.409c0-4.556 2.558-7.83 5.739-11.01C22.168 9.813 21.272 5.5 28.733 5.5c6.136 0 11.107 4.979 11.107 11.114z");
}

</style>
