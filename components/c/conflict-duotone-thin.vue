<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y65anc6av"/><path class="wgfzeno5h"/><path class="uhvqpxb1w"/><path class="y9euribju"/><path class="bs41d9oln"/><path class="erdfj7vbx"/><path class="o_nzgwnjk"/><path class="vtgsa7bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:conflict-duotone-thin" /></template>
<style>
.bs41d9oln {
  d: path("m3 3 5 5");
}

.erdfj7vbx {
  d: path("M10.5 7v3.5H7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_nzgwnjk {
  d: path("m21 21 -5 -5");
}

.uhvqpxb1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 21 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vtgsa7bep {
  d: path("M13.5 17v-3.5H17");
}

.wgfzeno5h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 7v3.5H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y65anc6av {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 3 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y9euribju {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 17v-3.5H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
