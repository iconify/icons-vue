<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="qude_sb_h"/><path class="jpzrzuhsz"/><path class="ky4omnbla"/><path class="y5k8b5bfa"/><path class="nm1qcabkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bill-reminder-duotone-bold" /></template>
<style>
.jpzrzuhsz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 10h5v4H9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.nm1qcabkz {
  d: path("M9 10h5v4H9");
}

.qude_sb_h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4wfbu4kp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

</style>
