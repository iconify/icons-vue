<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qecovn3xi"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="acai3yb8w"/><path class="zqjox4bdd"/><path class="xp1r03_dy"/><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="jah0pzsgs"/><path class="a10g3vbao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-pull-request-draft-duotone-thin" /></template>
<style>
.a10g3vbao {
  d: path("M18 7v3");
}

.acai3yb8w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.jah0pzsgs {
  d: path("M18 12.5v4");
}

.jz0b4rbqp {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k5nz3bcao {
  d: path("M6 7.5v9");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.st2iv5bfu {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xp1r03_dy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zqjox4bdd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12.5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
