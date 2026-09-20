<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qecovn3xi"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="acai3yb8w"/><path class="u8foyusdc"/><path class="w35wu23wu"/><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="w7fxcjk_f"/><path class="l_raegbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-pull-request-create-duotone-thin" /></template>
<style>
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

.l_raegbyq {
  d: path("M15.5 6.5h5");
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

.u8foyusdc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w35wu23wu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 6.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w7fxcjk_f {
  d: path("M18 4v5");
}

</style>
