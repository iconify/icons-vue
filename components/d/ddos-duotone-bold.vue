<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k7xqwbc0e"/><path class="m1_t8eblw"/><path class="g-jmfdcne"/><path class="p53i0is_x"/><path class="q84dtjb2k"/><path class="ghf2zyulc"/><path class="lpi5lkbmw"/><path class="wr9epib_z"/><path class="ka1ksx6kt"/><path class="u649he-6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ddos-duotone-bold" /></template>
<style>
.g-jmfdcne {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghf2zyulc {
  d: path("M2 5h12");
}

.k7xqwbc0e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ka1ksx6kt {
  d: path("M2 19h12");
}

.lpi5lkbmw {
  d: path("M2 9h12");
}

.m1_t8eblw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p53i0is_x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q84dtjb2k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u649he-6w {
  d: path("M18 3v18");
}

.wr9epib_z {
  d: path("M2 15h12");
}

</style>
