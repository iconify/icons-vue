<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="im-4rpp6h"/><path class="n1m48jnmi"/><path class="b4vokcbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horse" /></template>
<style>
.b4vokcbqq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 9.75h.01");
}

.im-4rpp6h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 21.25h-7.5c0-2.25.75-4 .75-5.75c-1.25.75-3 1.25-4.75 1.5c-1.4.2-2.5-.75-2.5-2c0-.6.25-1.15.7-1.55L10.5 7c.75-.75 1.75-1.25 2.75-1.5l.5-2.5l1.75 2.25c2.75.75 4.75 3.5 4.75 7c0 3.75-2.5 6-2.5 9");
}

.n1m48jnmi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 7.5c1.5 1.5 2 3.25 1.75 5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
