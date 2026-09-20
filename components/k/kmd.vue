<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnIkdyb1p)" class="v0r91qk_x"/><path fill="url(#SVGfJgLFcRM)" class="cppwvh3al"/><defs><linearGradient id="SVGnIkdyb1p" x1="17.53" x2="7.845" y1="5.315" y2="19.216" gradientUnits="userSpaceOnUse"><stop class="ol6smbaie"/><stop offset="1" class="gcy5q2btu"/></linearGradient><linearGradient id="SVGfJgLFcRM" x1="17.252" x2="11.501" y1="6.062" y2="14.315" gradientUnits="userSpaceOnUse"><stop class="ol6smbaie"/><stop offset="1" class="gcy5q2btu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kmd" /></template>
<style>
.cppwvh3al {
  d: path("M19.312 6.375a1.687 1.687 0 0 1-1.688 1.687c-.483 0-1.014.042-1.355.383l-.526.525c-.59.591-.607 1.526-.438 2.343a3.374 3.374 0 1 1-2.684-2.63c.799.148 1.703.116 2.278-.46l.688-.688c.295-.294.35-.743.35-1.16a1.688 1.688 0 0 1 3.375 0");
}

.ft5dv1b6b {
  fill: none;
}

.gcy5q2btu {
  stop-color: var(--svg-color--1b456e, #1b456e);
}

.ol6smbaie {
  stop-color: var(--svg-color--00ecd2, #00ecd2);
}

.v0r91qk_x {
  d: path("M12 4.687A7.312 7.312 0 1 0 19.312 12c0-.866-.15-1.697-.425-2.465a.844.844 0 0 1 1.588-.57A9 9 0 0 1 12 21a9 9 0 0 1-9-9a9 9 0 0 1 11.754-8.57a.844.844 0 0 1-.516 1.606A7.3 7.3 0 0 0 12 4.687");
}

</style>
