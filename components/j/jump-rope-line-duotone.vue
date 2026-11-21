<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtv4e2bwy"/><path class="bh8rq4bww"/><path class="k24fzt-4w"/><path class="xp_e2k-7l"/><path class="xn8s9lb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jump-rope-line-duotone" /></template>
<style>
.bh8rq4bww {
  d: path("M18.5 6.75V4C18.5 3.2929 18.5 2.9394 18.7197 2.7197C18.9394 2.5 19.2929 2.5 20 2.5C20.7071 2.5 21.0606 2.5 21.2803 2.7197C21.5 2.9394 21.5 3.2929 21.5 4V9.5C21.5 10.2071 21.5 10.5607 21.2803 10.7803C21.0606 11 20.7071 11 20 11C19.2929 11 18.9394 11 18.7197 10.7803C18.5 10.5607 18.5 10.2071 18.5 9.5V6.75Z");
}

.dtv4e2bwy {
  d: path("M2.5 17.25V14.5C2.5 13.7929 2.5 13.4393 2.7197 13.2197C2.9394 13 3.2929 13 4 13C4.7071 13 5.0606 13 5.2803 13.2197C5.5 13.4393 5.5 13.7929 5.5 14.5V20C5.5 20.7071 5.5 21.0606 5.2803 21.2803C5.0606 21.5 4.7071 21.5 4 21.5C3.2929 21.5 2.9394 21.5 2.7197 21.2803C2.5 21.0606 2.5 20.7071 2.5 20V17.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k24fzt-4w {
  d: path("M4 13V6.5C4 4.2909 5.7909 2.5 8 2.5C10.2091 2.5 12 4.2909 12 6.5V17.5C12 19.7091 13.7909 21.5 16 21.5C18.2091 21.5 20 19.7091 20 17.5V11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xn8s9lb2i {
  d: path("M18.5 8H21.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xp_e2k-7l {
  d: path("M2.5 16H5.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
