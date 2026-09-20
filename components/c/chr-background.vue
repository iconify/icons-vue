<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b1j5d5brf"/><path class="t9symeb1j"/><path class="j91ybob-n"/><path class="lamhgqbdi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:chr-background" /></template>
<style>
.b1j5d5brf {
  fill: var(--svg-color--ffb0c2, #ffb0c2);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.j91ybob-n {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.022 9.547a3.25 3.25 0 0 0 1.2-2.454A3.1 3.1 0 0 0 15.112 4A3.12 3.12 0 0 0 12 7.111h.178c1.982 0 3.702.978 4.844 2.436");
}

.lamhgqbdi {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.116 10.182c.746 0 1.373-.209 1.906-.64a6.1 6.1 0 0 0-4.844-2.43H12a3.094 3.094 0 0 0 3.111 3.07z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t9symeb1j {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.906 15.111c-.533 1.031-1.6 1.778-2.818 1.778c-1.91 0-3.213-1.342-3.2-3.316c.014-1.973 1.272-3.35 3.2-3.35A3.23 3.23 0 0 1 14.907 12h3.316c-.667-2.831-3.156-4.889-6.134-4.889c-3.484 0-6.31 2.889-6.31 6.445c0 3.555 2.826 6.444 6.31 6.444c2.97 0 5.458-2.071 6.134-4.889z");
}

</style>
