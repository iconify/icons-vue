<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a8pimuien"/><path class="o4z13cbej"/><path class="kf_l73bfg"/><path class="uq0j59epz"/><path class="jip36lb6o"/><path class="bbj4iccle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kex" /></template>
<style>
.a8pimuien {
  fill: var(--svg-color--298dff, #298dff);
  d: path("M4.35 8.512c-.349.192-.787.158-.787-.247v-1.67L9.885 3v1.67c0 .406-.281.9-.653 1.092L4.35 8.518z");
}

.bbj4iccle {
  fill: var(--svg-color--4264f2, #4264f2);
  d: path("M14.886 17.018c-.338.197-.636.045-.636-.36V10.92c0-.405.276-.9.636-1.091l5.552-3.234v7.194z");
}

.ft5dv1b6b {
  fill: none;
}

.jip36lb6o {
  fill: var(--svg-color--344ae6, #344ae6);
  d: path("M5.25 10.763c0-.411.298-.563.692-.366l5.366 2.92A1.41 1.41 0 0 1 12 14.418V21l-6.75-3.656z");
}

.kf_l73bfg {
  fill: var(--svg-color--4264f2, #4264f2);
  d: path("M18.863 5.756c-.36-.185-.675-.04-.675.371v5.738c0 .405.292.9.675 1.085l1.518.839V6.594l-1.518-.832z");
}

.o4z13cbej {
  fill: var(--svg-color--344ae6, #344ae6);
  d: path("M13.463 20.167c.349-.197.349-.54 0-.732l-5.034-2.868a1.5 1.5 0 0 0-1.283 0l-1.457.838l6.323 3.594l1.457-.832z");
}

.uq0j59epz {
  fill: var(--svg-color--298dff, #298dff);
  d: path("M3.563 6.6L9.885 3l5.687 3.234c.349.192.349.535 0 .726l-5.04 2.869c-.343.191-.934.191-1.277 0L3.562 6.594z");
}

</style>
