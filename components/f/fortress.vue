<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="o7szooqoa"/><path class="jlam6hxfq"/><path class="crng-cbuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fortress" /></template>
<style>
.crng-cbuv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12.25h.01m13.99 0h.01");
}

.jlam6hxfq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 21.25V18a2.25 2.25 0 0 1 4.5 0v3.25");
}

.o7szooqoa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.78 20.8l.69-11.85q.03-.45.48-.45h2.1q.45 0 .45.45v3.1q0 .45.45.45h1.3q.45 0 .45-.45v-.85q0-.45.45-.45h1.3q.45 0 .45.45v.85q0 .45.45.45h1.3q.45 0 .45-.45v-.85q0-.45.45-.45h1.3q.45 0 .45.45v.85q0 .45.45.45h1.3q.45 0 .45-.45v-3.1q0-.45.45-.45h2.1q.45 0 .48.45l.69 11.85q.03.45-.42.45H3.2q-.45 0-.42-.45");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
