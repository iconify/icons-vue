<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dorv6lczq"/><path class="zkj2o_y4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-play-two-tone" /></template>
<style>
.dorv6lczq {
  stroke-opacity: 0.4;
  d: path("M5 16.874C3.2748 16.4299 2 14.8638 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.8638 20.7252 16.4299 19 16.874");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zkj2o_y4k {
  d: path("M10.5998 13.2016L14.5998 16.1998C15.1334 16.5998 15.1334 17.4002 14.5998 17.8002L10.5998 20.7984C9.9405 21.2925 9 20.8221 9 19.9982L9 14.0018C9 13.1779 9.9405 12.7075 10.5998 13.2016Z");
}

</style>
