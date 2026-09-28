<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o15_wxb5r"/><path class="jnp5spbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:golf-hole-duotone" /></template>
<style>
.jnp5spbfs {
  fill: currentColor;
  d: path("M10 3.6937C9.9999 2.8653 10.6714 2.1937 11.4999 2.1937C11.6611 2.1937 11.8213 2.2197 11.9743 2.2707L17.4702 4.1026C18.2869 4.3749 18.8377 5.1391 18.8377 6C18.8377 6.8609 18.2869 7.6251 17.4702 7.8974L11.9743 9.7293C11.8213 9.7803 11.6611 9.8063 11.4999 9.8063C10.6714 9.8063 9.9999 9.1347 10 8.3063L10 3.6937Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o15_wxb5r {
  stroke-opacity: 0.4;
  d: path("M15 15.1373C19.0571 15.5196 22 16.6567 22 18C22 19.6569 17.5228 21 12 21C6.4772 21 2 19.6569 2 18C2 16.8895 4.011 15.92 7 15.4013M11 3L11 17");
}

</style>
