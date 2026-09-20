<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":193};
const content = `<path class="idgcvfhqm"/><path class="cloqfx-6x"/><path class="y6vfw_b4w"/><path class="h64oqabrn"/><path class="o501xdb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-gmail-2020" /></template>
<style>
.cloqfx-6x {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M197.818 192.05h40.727c9.659 0 17.455-7.826 17.455-17.455V49.505l-31.156 17.837l-27.026 25.798z");
}

.h64oqabrn {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("M197.818 17.504V93.14L256 49.504V26.231c0-21.585-24.64-33.89-41.89-20.945z");
}

.idgcvfhqm {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M58.182 192.05V93.14L27.507 65.077L0 49.504v125.091c0 9.658 7.825 17.455 17.455 17.455z");
}

.o501xdb5q {
  fill: var(--svg-color--c5221f, #c5221f);
  d: path("m0 49.504l26.759 20.07L58.182 93.14V17.504L41.89 5.286C24.61-7.66 0 4.646 0 26.23z");
}

.y6vfw_b4w {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("m58.182 93.14l-4.174-38.647l4.174-36.989L128 69.868l69.818-52.364l4.669 34.992l-4.669 40.644L128 145.504z");
}

</style>
