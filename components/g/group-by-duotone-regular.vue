<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asw7rwc8o"/><path class="q5mfembzm"/><path class="o10durn9i"/><path class="q5fdyummg"/><path class="w2bwi-bro"/><path class="ybh1xwgpp"/><path class="qfe94rk-q"/><path class="ygvoi9umd"/><path class="hxoe7gx5p"/><path class="vox58lg-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-by-duotone-regular" /></template>
<style>
.asw7rwc8o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o10durn9i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5fdyummg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5mfembzm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 11h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qfe94rk-q {
  d: path("M2 11h8");
}

.vox58lg-w {
  d: path("M12 11h10");
}

.w2bwi-bro {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ybh1xwgpp {
  d: path("M2 5h8");
}

.ygvoi9umd {
  d: path("M2 17h8");
}

</style>
