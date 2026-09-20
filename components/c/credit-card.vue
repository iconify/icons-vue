<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGJORAzdgL" class="k-q5egb2m"/></defs><use href="#SVGJORAzdgL" class="j71m3fb1u"/><clipPath id="SVGlbgyOdbd"><use href="#SVGJORAzdgL"/></clipPath><path clip-path="url(#SVGlbgyOdbd)" class="kesa08bwr"/><path class="eczgzm16a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:credit-card" /></template>
<style>
.eczgzm16a {
  fill: var(--svg-color--fff, #fff);
  d: path("M119.26 64.62c1.14 1.5.98 3.3-.4 3.99l-11.09 5.66c-1.43.73-3.54.05-4.68-1.51l-6.51-8.93c-1.09-1.51-.82-3.29.6-3.97l11.03-5.25c1.36-.65 3.36 0 4.48 1.44z");
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.k-q5egb2m {
  d: path("M125.76 64.91c2.32 2.99 2.04 6.61-.68 8.03l-82.41 43.15c-3.62 1.88-8.38.33-10.54-3.45L1.46 59.07c-1.79-3.13-.4-6.8 3.03-8.17l79.49-31.67c2.66-1.05 6.41.15 8.39 2.7z");
}

.kesa08bwr {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M106.86 35.82L8.43 79.41L-.02 64.45l97.55-40.54z");
}

</style>
