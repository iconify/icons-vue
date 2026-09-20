<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="aadb6p4zd"/><path class="bzahnn5hm"/><path class="ua5xrvbgy"/><path class="sgz4ahb8b"/><path class="jdfiqjznk"/><ellipse class="ut88s5nmg"/><ellipse class="ajdb3329a"/><path class="pxqd_j1oz"/><path class="adl58xb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-ceuta-and-melilla" /></template>
<style>
.aadb6p4zd {
  fill: var(--svg-color--c60a1d, #C60A1D);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

.adl58xb-d {
  fill: var(--svg-color--66757f, #66757F);
  d: path("M6 22h3v1H6zm9 0h3v1h-3zm-8-7h1v1H7zm9 0h1v1h-1z");
}

.ajdb3329a {
  fill: var(--svg-color--ffac33, #FFAC33);
  cx: 12px;
  cy: 13.75px;
  rx: 3px;
  ry: 0.75px;
}

.bzahnn5hm {
  fill: var(--svg-color--ffc400, #FFC400);
  d: path("M0 12h36v12H0z");
}

.jdfiqjznk {
  fill: var(--svg-color--dd2e44, #DD2E44);
  d: path("M9 16h3v3H9z");
}

.pxqd_j1oz {
  fill: var(--svg-color--99aab5, #99AAB5);
  d: path("M7 16h1v7H7zm9 0h1v7h-1z");
}

.sgz4ahb8b {
  fill: var(--svg-color--f4a2b2, #F4A2B2);
  d: path("M12 16h3v3h-3z");
}

.ua5xrvbgy {
  fill: var(--svg-color--ea596e, #EA596E);
  d: path("M9 17v3a3 3 0 1 0 6 0v-3H9z");
}

.ut88s5nmg {
  fill: var(--svg-color--ea596e, #EA596E);
  cx: 12px;
  cy: 14.5px;
  rx: 3px;
  ry: 1.5px;
}

</style>
