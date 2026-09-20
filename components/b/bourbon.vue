<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":252};
const content = `<defs><linearGradient id="SVGS2L3pdzI" x1="46.646%" x2="57.363%" y1="-2.089%" y2="137.781%"><stop offset="0%" class="nm6j3zbxl"/><stop offset="63.5%" class="ytysp4lag"/><stop offset="100%" class="gw_1qmypk"/></linearGradient></defs><path class="znaynxssx"/><path class="e7rj-lbwn"/><ellipse class="ubzovcbzb"/><path fill="url(#SVGS2L3pdzI)" class="zwtm43bms"/><path class="yskcxrbaj"/><path class="l69r2k1cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bourbon" /></template>
<style>
.e7rj-lbwn {
  fill: var(--svg-color--fef9ec, #fef9ec);
  d: path("M247.554 24.951c0-3.685-1.48-6.843-3.585-8.949c-5.44-6.316-55.271-8.422-116.333-8.422c-60.81 0-110.542 1.58-116.333 7.896c-2.13 2.632-3.684 5.264-3.684 8.949l.05 5.79c0 .526-.05 1.053.476 1.58c-.226.526 21.056 192.133 21.056 192.133c1.529 11.054 11.054 19.476 22.108 19.476h151.125c11.53 0 21.006-8.422 22.059-19.476h.25l22.56-192.134v-6.843z");
}

.gw_1qmypk {
  stop-color: var(--svg-color--e3302e, #e3302e);
}

.l69r2k1cv {
  fill: var(--svg-color--fef9ec, #fef9ec);
  d: path("M65.823 112.122c-5.014.526-8.347 5.264-7.821 10.001l5.314 41.585c.752 5.264 5.214 8.423 10.478 7.896l40.908-5.264c5.013-1.052 8.573-5.264 7.52-10.528l-5.013-41.585c-.752-4.737-5.515-8.422-10.252-7.37z");
  opacity: var(--svg-opacity--0-65, 0.65);
}

.nm6j3zbxl {
  stop-color: var(--svg-color--ff992e, #ff992e);
}

.ubzovcbzb {
  cx: 127.11px;
  cy: 23.372px;
  fill: var(--svg-color--e5d1bf, #e5d1bf);
  rx: 105.805px;
  ry: 5.79px;
}

.yskcxrbaj {
  fill: var(--svg-color--fef9ec, #fef9ec);
  d: path("M97.156 136.336c-3.008 3.685-2.306 9.475 1.905 12.633l32.686 25.794c4.01 2.632 9.952 2.105 12.584-2.106l25.517-33.163c3.008-3.684 2.381-9.475-1.83-12.633l-32.761-25.793c-4.011-2.632-9.877-2.106-13.035 2.105z");
  opacity: var(--svg-opacity--0-65, 0.65);
}

.ytysp4lag {
  stop-color: var(--svg-color--ff4c2e, #ff4c2e);
}

.znaynxssx {
  fill: var(--svg-color--e5d1bf, #e5d1bf);
  d: path("M51.535 251.616c-15.04 0-27.749-11.58-29.854-26.32C21.455 223.191.625 34.742.625 32.636C.4 32.11.1 31.584.1 31.057l.05-6.317c0-5.263 2.055-10.527 6.266-13.686C9.925 6.317 17.996 0 128.012 0C237.778 0 245.924 6.317 249.61 11.054c3.71 3.685 5.79 8.423 5.79 14.213l-.075 5.264c0 1.053.076 1.579-.45 2.632l-22.36 192.133c0 .527-.276 1.053-.276 1.58c-2.732 14.212-15.265 24.74-29.478 24.74z");
}

.zwtm43bms {
  d: path("M213.965 205.504c-.25 6.843-5.264 12.107-12.107 12.107H52.287c-6.517 0-11.506-5.264-12.032-12.107c-1.003-17.897-7.37-71.59-7.37-71.59c-.15-4.737 2.106-7.369 7.37-7.369h173.71c4.762 0 7.37 2.632 7.37 7.37c.15 0-6.844 53.692-7.37 71.59");
}

</style>
