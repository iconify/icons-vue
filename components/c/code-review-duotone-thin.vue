<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="saqbxe1ne"/><path class="blpqvobsg"/><path class="gh_b-0fuf"/><path class="lrkxnckco"/><path class="aoorvnbzq"/><path class="e-eh9i0mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-review-duotone-thin" /></template>
<style>
.aoorvnbzq {
  d: path("m14 7 4 4 -4 4");
}

.blpqvobsg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 7 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e-eh9i0mi {
  d: path("m9 19 2 2 4 -4");
}

.gh_b-0fuf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 19 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrkxnckco {
  d: path("m8 7 -4 4 4 4");
}

.saqbxe1ne {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 7 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
