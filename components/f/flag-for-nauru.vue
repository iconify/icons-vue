<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hxpq6krdi"/><path class="nw9ymfbwo"/><path class="mtfln50gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-nauru" /></template>
<style>
.hxpq6krdi {
  fill: var(--svg-color--002b7f, #002B7F);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

.mtfln50gp {
  fill: var(--svg-color--fff, #FFF);
  d: path("M9.979 19.479l.492 1.965l1.409-1.456l-.556 1.949l1.949-.557l-1.457 1.409l1.966.492l-1.966.492l1.457 1.41l-1.949-.557l.556 1.949l-1.409-1.457l-.492 1.966l-.492-1.966l-1.409 1.457l.556-1.949l-1.948.557l1.456-1.41l-1.966-.492l1.966-.492l-1.456-1.409l1.948.557l-.556-1.949l1.409 1.456z");
}

.nw9ymfbwo {
  fill: var(--svg-color--ffc61e, #FFC61E);
  d: path("M0 17h36v2H0z");
}

</style>
