<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVG3TvBAdnd" cx="64" cy="88.158" r="52.794" gradientTransform="matrix(1 0 0 .43924 0 49.436)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="kkzn698ce"/><stop offset=".751" class="oxgxalihh"/><stop offset=".97" class="hunkxc7oa"/></radialGradient><ellipse fill="url(#SVG3TvBAdnd)" class="y8__9db2c"/><path class="vyiyt1bmc"/><linearGradient id="SVGdcHHjcWs" x1="63.925" x2="63.925" y1="82.747" y2="116.012" gradientUnits="userSpaceOnUse"><stop offset="0" class="a72as_i6q"/><stop offset=".305" class="b8534puqy"/><stop offset=".87"/></linearGradient><path fill="url(#SVGdcHHjcWs)" class="r18j87gwg"/><path class="ajg0y9ure"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:hole" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.ajg0y9ure {
  fill: var(--svg-color--9e9e9e, #9e9e9e);
  d: path("M64 67.493c32.07 0 56.034 10.91 56.034 20.665c0 4.564-5.529 9.619-14.788 13.521c-10.934 4.607-25.582 7.145-41.246 7.145c-32.07 0-56.034-10.91-56.034-20.666c0-4.564 5.529-9.618 14.788-13.52C33.688 70.03 48.336 67.493 64 67.493m0-4.619c-33.137 0-60 11.32-60 25.284s26.863 25.285 60 25.285s60-11.32 60-25.285s-26.863-25.284-60-25.284");
}

.b8534puqy {
  stop-color: var(--svg-color--222, #222);
}

.hunkxc7oa {
  stop-color: var(--svg-color--9e9e9e, #9e9e9e);
}

.kkzn698ce {
  stop-color: var(--svg-color--adadad, #adadad);
}

.oxgxalihh {
  stop-color: var(--svg-color--a3a3a3, #a3a3a3);
}

.r18j87gwg {
  d: path("M115.755 96.242C107.11 88.048 86.652 81.456 64 81.456c-22.678 0-43.274 6.506-51.905 14.715C20.203 103.21 27.4 109.99 64 109.99s49.28-11.588 51.755-13.75");
}

.vyiyt1bmc {
  fill: var(--svg-color--757575, #757575);
  d: path("M27.681 69.302C9.336 75.109 6.758 82.304 6.758 88.567c0 6.441 11.988 12.29 21.732 16.623zm72.774-.409l-.808 35.888c9.743-4.333 21.731-10.182 21.731-16.623c0-6.263-6.524-15.795-20.923-19.265");
}

.y8__9db2c {
  cx: 64px;
  cy: 88.158px;
  rx: 60px;
  ry: 25.284px;
}

</style>
