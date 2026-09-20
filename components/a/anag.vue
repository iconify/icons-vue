<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jue6gw0go"/><g class="y9tr6bcfx"><path class="p71nhbbqt"/><path class="nshw-0bdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anag" /></template>
<style>
.jue6gw0go {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.094 22.36l.083 19.898l1.256 1.242h3.32l1.535-1.242V28.72l9.7 14.298h4.952l.967-1.327V22.36H28.69v10.37l-6.636-10.37z");
}

.nshw-0bdr {
  d: path("M24 6.13zc6.024 0 10.907 4.883 10.907 10.907v1.556H13.094v-1.556C13.094 11.013 17.977 6.13 24 6.13M14.582 4.5l3.098 3.647M33.418 4.5L30.32 8.147");
}

.p71nhbbqt {
  d: path("M19.556 15.55a1.53 1.53 0 1 1 0-3.06a1.53 1.53 0 0 1 0 3.06m8.905 0a1.53 1.53 0 1 1 1.53-1.53a1.53 1.53 0 0 1-1.53 1.53");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
