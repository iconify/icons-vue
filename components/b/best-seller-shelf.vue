<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftuj_0fvz"/><path class="pz-dd1b4h"/><path class="ugca5xcfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:best-seller-shelf" /></template>
<style>
.ftuj_0fvz {
  d: path("M4 15h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 18H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pz-dd1b4h {
  d: path("M6.5 18H7a.751.751 0 0 1 .495 1.317l-1.178 1.031A.794.794 0 0 1 5 19.75v-.25A1.5 1.5 0 0 1 6.5 18m11 0H17a.751.751 0 0 0-.495 1.317l1.178 1.031A.794.794 0 0 0 19 19.75v-.25a1.5 1.5 0 0 0-1.5-1.5M8 2.5h8V6a4 4 0 0 1-8 0Z");
}

.ugca5xcfo {
  d: path("M8 4H6.25c-.75 0-1 .75-.75 1.5c.4 1.25 1.25 2.25 2.75 2.75M16 4h1.75c.75 0 1 .75.75 1.5c-.4 1.25-1.25 2.25-2.75 2.75M12 10v2.5m-1.75 0h3.5A1.25 1.25 0 0 1 15 13.75A1.25 1.25 0 0 1 13.75 15h-3.5A1.25 1.25 0 0 1 9 13.75a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
