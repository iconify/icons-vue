<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":223};
const content = `<defs><linearGradient id="SVGqO8x7bFz" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="j29v80bft"/><stop offset="100%" class="hgucklndm"/></linearGradient><linearGradient id="SVGx4gMLewF" x1="74.943%" x2="19.813%" y1="95.826%" y2="-4.161%"><stop offset="0%" class="se0uceyql"/><stop offset="100%" class="clthtq7lj"/></linearGradient><linearGradient id="SVGyiFpAPcn" x1="59.898%" x2="21.416%" y1="-.134%" y2="99.86%"><stop offset="0%" class="ea5snh66u"/><stop offset="100%" class="v2atxxbiw"/></linearGradient><path id="SVGxaPpebGJ" class="vg7slnbvt"/></defs><path class="nlzpwhfym"/><path class="o_yya3ebg"/><path class="hdn5ldx2m"/><mask id="SVGLoBU3cAy" class="n1mjunbsu"><use href="#SVGxaPpebGJ"/></mask><g mask="url(#SVGLoBU3cAy)"><g transform="translate(17.455 94.293)"><path fill="url(#SVGqO8x7bFz)" class="qowr-fbwy"/><path fill="url(#SVGx4gMLewF)" class="z4scfabbt"/><path fill="url(#SVGyiFpAPcn)" class="oy-bey06d"/><ellipse class="x68w3nf0l"/><ellipse class="sx7nx7bjc"/></g></g><path class="hwrjw4q0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:chrome-web-store" /></template>
<style>
.clthtq7lj {
  stop-color: var(--svg-color--34a853, #34a853);
}

.ea5snh66u {
  stop-color: var(--svg-color--fbbc04, #fbbc04);
}

.hdn5ldx2m {
  fill: var(--svg-color--fff, #fff);
  d: path("M157.076 47.727H98.907A11.63 11.63 0 0 1 87.27 36.09a11.63 11.63 0 0 1 11.637-11.637h58.169a11.63 11.63 0 0 1 11.637 11.637c0 6.417-5.204 11.637-11.637 11.637");
}

.hgucklndm {
  stop-color: var(--svg-color--ea4335, #ea4335);
}

.hwrjw4q0p {
  fill: var(--svg-color--bdc1c6, #bdc1c6);
  d: path("M0 111.74h255.983v1.448H0zm0-1.465h255.983v1.448H0z");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.j29v80bft {
  stop-color: var(--svg-color--d93025, #d93025);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nlzpwhfym {
  fill: var(--svg-color--f1f3f4, #f1f3f4);
  d: path("M255.983 0H0v204.837c0 9.633 7.814 17.464 17.464 17.464h221.072c9.633 0 17.464-7.814 17.464-17.464z");
}

.o_yya3ebg {
  fill: var(--svg-color--e8eaed, #e8eaed);
  d: path("M0 0h255.983v111.74H0z");
}

.oy-bey06d {
  d: path("M206.26 55.272h-95.724l47.862 82.908l-47.862 82.925c38.162-.033 75.263-19.855 95.708-55.289c20.461-35.433 19.064-77.468.016-110.544");
}

.qowr-fbwy {
  d: path("m14.812 55.255l15.241 46.498l32.638 36.427l47.845-82.908l95.724-.017C187.146 22.213 151.443 0 110.536 0s-76.61 22.213-95.724 55.255");
}

.se0uceyql {
  stop-color: var(--svg-color--1e8e3e, #1e8e3e);
}

.sx7nx7bjc {
  cx: 110.536px;
  cy: 110.544px;
  fill: var(--svg-color--1a73e8, #1a73e8);
  rx: 44.898px;
  ry: 44.915px;
}

.v2atxxbiw {
  stop-color: var(--svg-color--fcc934, #fcc934);
}

.vg7slnbvt {
  d: path("M255.983 0H0v204.837c0 9.633 7.814 17.464 17.464 17.464h221.072c9.633 0 17.464-7.814 17.464-17.464z");
}

.x68w3nf0l {
  cx: 110.536px;
  cy: 110.544px;
  fill: var(--svg-color--f1f3f4, #f1f3f4);
  rx: 55.255px;
  ry: 55.272px;
}

.z4scfabbt {
  d: path("m110.52 221.105l32.637-36.443l15.224-46.482H62.674L14.812 55.255c-19.047 33.076-20.445 75.128.017 110.561c20.445 35.434 57.545 55.256 95.69 55.29");
}

</style>
