<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z_kyaub1a"/><path class="avs4gwqsk"/><path class="cj2qtk9vr"/><path class="dn-17_b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-sync" /></template>
<style>
.avs4gwqsk {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.769 0 1.498-.049m6.374-2.215A1 1 0 0 0 20 12");
}

.cj2qtk9vr {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5M20.75 18A2.75 2.75 0 1 1 18 15.25");
}

.dn-17_b8d {
  d: path("M16.75 14L18 15.25l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_kyaub1a {
  d: path("M13.488 21.202q-.725.047-1.488.048c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.955");
}

</style>
