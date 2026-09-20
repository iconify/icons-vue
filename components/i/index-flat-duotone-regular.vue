<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wpykkrwot"/><path class="k37bm_bip"/><path class="kbd2vhccj"/><path class="hl6ybeb4u"/><path class="b6daa3b4n"/><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-flat-duotone-regular" /></template>
<style>
.b6daa3b4n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 13 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bvj__8b4y {
  d: path("M20 4v11");
}

.hl6ybeb4u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.isrkj8blm {
  d: path("M3 17h13");
}

.k37bm_bip {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kbd2vhccj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrc90qj9p {
  d: path("m18 13 2 2 2 -2");
}

.uilxv67me {
  d: path("M3 11h13");
}

.wpykkrwot {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-vga5bbj {
  d: path("M3 5h13");
}

</style>
