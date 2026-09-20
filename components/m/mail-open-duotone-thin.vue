<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8848ubds"/><path class="nd9of9b4e"/><path class="g8vwx15sp"/><path class="ckawxab4i"/><path class="zr5lbkq8n"/><path class="ujkepejes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-open-duotone-thin" /></template>
<style>
.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.g8vwx15sp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 12 6 6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd9of9b4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11v10h16V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ujkepejes {
  d: path("m6 12 6 6 6 -6");
}

.v8848ubds {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zr5lbkq8n {
  d: path("M4 11v10h16V11");
}

</style>
