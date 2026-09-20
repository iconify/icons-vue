<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient x1="50%" y1="0%" x2="50%" y2="100%" id="ssvg-id-horizona"><stop offset="0%" class="q17zedc8l"/><stop offset="100%" class="kojdo3bnu"/></linearGradient><path id="ssvg-id-horizonb" class="ayxx_sbvs"/></defs><path fill="url(#ssvg-id-horizona)" class="vjpewwwet"/><path class="jeux9ccnt"/><use xlink:href="#ssvg-id-horizonb" class="xeqsa7bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:horizon" /></template>
<style>
.ayxx_sbvs {
  d: path("M215.923 163.987c-16.153 3.476-82.471 5.452-82.675 12.745c.204 8.52 40.008 8.792 39.327 18.062c-1.26 16.906-63.717 26.911-124.144 33.467C70.278 245.623 97.925 256 128 256c66.386 0 120.962-50.541 127.365-115.243c-10.915 10.833-21.176 19.141-39.442 23.23z");
}

.jeux9ccnt {
  d: path("M.002 128.136C.076 198.766 57.353 256 128 256s127.924-57.234 127.998-127.864H.002z");
  fill: var(--svg-color--62b3c5, #62B3C5);
}

.kojdo3bnu {
  stop-color: var(--svg-color--fbb583, #FBB583);
}

.q17zedc8l {
  stop-color: var(--svg-color--e7507e, #E7507E);
}

.vjpewwwet {
  d: path("M0 128l.002.136l1.997 1.333H79.5l2.299-1.333c.221-26.01 21.366-47.028 47.428-47.028c26.062 0 47.206 21.018 47.427 47.028l3.013 1.5h74.665l1.666-1.5L256 128C256 57.307 198.692 0 128 0C57.308 0 0 57.307 0 128z");
}

.xeqsa7bam {
  fill: var(--svg-color--a8dce3, #A8DCE3);
}

</style>
