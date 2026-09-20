<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzeve79sx"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="rti06vbvy"/><path class="p87uj9o3x"/><path class="xlqos5b9o"/><path class="ymw3aibdo"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="t2l4a8b-m"/><path class="cq87c55hm"/><path class="erxvlz1uk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-fork-duotone-thin" /></template>
<style>
.cq87c55hm {
  d: path("m12 11 -5.5 5.5");
}

.erxvlz1uk {
  d: path("m12 11 5.5 5.5");
}

.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz0b4rbqp {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p87uj9o3x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 11 -5.5 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rti06vbvy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.st2iv5bfu {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t2l4a8b-m {
  d: path("M12 7.5V11");
}

.xlqos5b9o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 11 5.5 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
