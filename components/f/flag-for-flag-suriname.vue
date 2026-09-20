<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="beiqp9bva"/><path class="qgqgc2bry"/><path class="vz8df2b_l"/><path class="h1ydkruah"/><path class="vdahx1b7p"/><path class="u1g65ac0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-suriname" /></template>
<style>
.beiqp9bva {
  fill: var(--svg-color--377e3f, #377e3f);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-1H0z");
}

.h1ydkruah {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 10h36v3H0z");
}

.qgqgc2bry {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 23h36v3H0z");
}

.u1g65ac0e {
  fill: var(--svg-color--ecc81d, #ecc81d);
  d: path("M14.944 22.703L18 20.483l3.056 2.22l-1.167-3.593l3.056-2.22h-3.778L18 13.297l-1.167 3.593h-3.778l3.056 2.22z");
}

.vdahx1b7p {
  fill: var(--svg-color--b40a2d, #b40a2d);
  d: path("M0 23h36V13H0zm16.833-6.11L18 13.297l1.167 3.593h3.778l-3.057 2.221l1.167 3.593L18 20.483l-3.056 2.221l1.167-3.593l-3.057-2.221z");
}

.vz8df2b_l {
  fill: var(--svg-color--377e3f, #377e3f);
  d: path("M32 5H4a4 4 0 0 0-4 4v1h36V9a4 4 0 0 0-4-4");
}

</style>
