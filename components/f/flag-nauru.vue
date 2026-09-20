<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e8e7ydbal"/><path class="h9sbklbah"/><path class="x9yjsaclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-nauru" /></template>
<style>
.e8e7ydbal {
  fill: var(--svg-color--002b7f, #002b7f);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.h9sbklbah {
  fill: var(--svg-color--ffc61e, #ffc61e);
  d: path("M0 17h36v2H0z");
}

.x9yjsaclt {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.979 19.479l.492 1.965l1.409-1.456l-.556 1.949l1.949-.557l-1.457 1.409l1.966.492l-1.966.492l1.457 1.41l-1.949-.557l.556 1.949l-1.409-1.457l-.492 1.966l-.492-1.966l-1.409 1.457l.556-1.949l-1.948.557l1.456-1.41l-1.966-.492l1.966-.492l-1.456-1.409l1.948.557l-.556-1.949l1.409 1.456z");
}

</style>
