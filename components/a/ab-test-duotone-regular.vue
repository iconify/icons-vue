<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="mdssbcbdg"/><path class="tuxsw9_hy"/><path class="zt_04q5ig"/><path class="nnwao2bjn"/><path class="tfzdxif4b"/><path class="kbcu0ebrl"/><path class="fg8libqda"/><path class="pw61xnbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ab-test-duotone-regular" /></template>
<style>
.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jz0b4rbqp {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kbcu0ebrl {
  d: path("m12 10 6 6");
}

.mdssbcbdg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nnwao2bjn {
  d: path("M12 3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.st2iv5bfu {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tfzdxif4b {
  d: path("m12 10 -6 6");
}

.tuxsw9_hy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 10 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zt_04q5ig {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 10 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
