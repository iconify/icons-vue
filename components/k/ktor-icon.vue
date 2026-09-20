<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGLKkSDb8c" x1="23.965%" x2="74.641%" y1="23.965%" y2="74.641%"><stop offset="29.6%" class="u8tcm6c4u"/><stop offset="69.4%" class="b9q93fweg"/><stop offset="100%" class="fm8fght5r"/></linearGradient><linearGradient id="SVG3A0aHc1h" x1="26.206%" x2="74.117%" y1="26.206%" y2="74.117%"><stop offset="10.8%" class="wocloqb2t"/><stop offset="17.3%" class="wd4kgkb9d"/><stop offset="49.2%" class="yed9zep2k"/><stop offset="71.6%" class="n9-hdgo3l"/><stop offset="82.3%" class="ygvu4sbcy"/></linearGradient></defs><path fill="url(#SVGLKkSDb8c)" class="s-ercmbuh"/><path fill="url(#SVG3A0aHc1h)" class="vt81uubzy"/><path class="wqxunacle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ktor-icon" /></template>
<style>
.b9q93fweg {
  stop-color: var(--svg-color--5282ff, #5282ff);
}

.fm8fght5r {
  stop-color: var(--svg-color--945dff, #945dff);
}

.n9-hdgo3l {
  stop-color: var(--svg-color--f88316, #f88316);
}

.s-ercmbuh {
  d: path("m170.667 85.333l-42.49-42.489L85.333 0L40.277 45.056L0 85.333l85.333 85.334z");
}

.u8tcm6c4u {
  stop-color: var(--svg-color--00afff, #00afff);
}

.vt81uubzy {
  d: path("m85.333 170.667l42.49 42.489L170.667 256l45.056-45.056L256 170.667l-85.333-85.334z");
}

.wd4kgkb9d {
  stop-color: var(--svg-color--cd5ca9, #cd5ca9);
}

.wocloqb2t {
  stop-color: var(--svg-color--c757bc, #c757bc);
}

.wqxunacle {
  d: path("M170.667 85.333H85.333v85.334h85.334z");
}

.yed9zep2k {
  stop-color: var(--svg-color--e8744f, #e8744f);
}

.ygvu4sbcy {
  stop-color: var(--svg-color--ff8900, #ff8900);
}

</style>
