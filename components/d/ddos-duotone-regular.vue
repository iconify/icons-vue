<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="itme0u7ra"/><path class="ul5lyibjg"/><path class="lzezl_bto"/><path class="h_vz08q8k"/><path class="xkw-kioym"/><path class="ghf2zyulc"/><path class="lpi5lkbmw"/><path class="wr9epib_z"/><path class="ka1ksx6kt"/><path class="u649he-6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ddos-duotone-regular" /></template>
<style>
.ghf2zyulc {
  d: path("M2 5h12");
}

.h_vz08q8k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.itme0u7ra {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ka1ksx6kt {
  d: path("M2 19h12");
}

.lpi5lkbmw {
  d: path("M2 9h12");
}

.lzezl_bto {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u649he-6w {
  d: path("M18 3v18");
}

.ul5lyibjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wr9epib_z {
  d: path("M2 15h12");
}

.xkw-kioym {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
