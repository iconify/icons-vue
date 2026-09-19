<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cj1-oca3i"/><path class="ocgtk9b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ella-2" /></template>
<style>
.cj1-oca3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.286 20.12v9.04m-4.508-6.309v3.579m9.215-7.675v11.771m4.508-10.406v9.04m4.507-6.309v3.579m5.026-13.905c8.37 6.251-2.412 30.318-11.025 30.088S5.5 33.943 5.5 25.502s24-20.098 33.534-12.977");
}

.ocgtk9b7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.377 5.577C17.221 3.127 4.704 24.934 10.381 31.416s23.247 11.361 29.744 5.972S38.944 8.367 27.377 5.577");
}

</style>
