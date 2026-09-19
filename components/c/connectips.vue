<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGPrrJWc1v" class="c-3_g2brf"/><path id="SVGwfFp7cth" class="a4-pghubg"/></defs><path class="z8yf-ttkh"/><use href="#SVGPrrJWc1v" class="c-zrgpb5l"/><use href="#SVGPrrJWc1v" class="c-zrgpb5l"/><path class="mx6dbg--c"/><path class="ovi2gr8jm"/><use href="#SVGwfFp7cth" class="c-zrgpb5l"/><use href="#SVGwfFp7cth" class="c-zrgpb5l"/><path class="zwfv4j4ss"/><path class="cn3om1bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:connectips" /></template>
<style>
.a4-pghubg {
  fill: none;
  stroke: currentColor;
  d: path("M33.25 35.682a9.24 9.24 0 0 0 9.25-9.23v-5.478a9.24 9.24 0 0 0-9.25-9.23a9.24 9.24 0 0 0-9.25 9.23v6.052a9.24 9.24 0 0 1-9.25 9.23a9.24 9.24 0 0 1-9.25-9.23v-5.478");
}

.c-3_g2brf {
  fill: none;
  stroke: currentColor;
  d: path("M35.682 14.75a9.24 9.24 0 0 0-9.23-9.25h-5.478a9.24 9.24 0 0 0-9.23 9.25a9.24 9.24 0 0 0 9.23 9.25h6.052a9.24 9.24 0 0 1 9.23 9.25a9.24 9.24 0 0 1-9.23 9.25h-5.478");
}

.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cn3om1bhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 12.318a9.24 9.24 0 0 0-9.25 9.23m9.25-9.23a13.6 13.6 0 0 1 4.536.672");
}

.mx6dbg--c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.682 14.75a13.6 13.6 0 0 1-.672 4.536M15.075 32.002l-2.085-3.288l-3.288 2.084m2.616 2.452a9.24 9.24 0 0 0 9.23 9.25");
}

.ovi2gr8jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.318 33.25a9.24 9.24 0 0 0 9.23 9.25m-9.23-9.25a13.6 13.6 0 0 1 .672-4.536m19.012 4.211l-3.288 2.085l2.084 3.288");
}

.z8yf-ttkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.925 15.998l2.085 3.288l3.288-2.084");
}

.zwfv4j4ss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 35.682a13.6 13.6 0 0 1-4.536-.672M15.998 15.075l3.288-2.085l-2.084-3.288m-2.452 2.616a9.24 9.24 0 0 0-9.25 9.23");
}

</style>
