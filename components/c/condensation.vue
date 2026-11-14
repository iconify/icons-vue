<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vavx96bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:condensation" /></template>
<style>
.vavx96bom {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.455 2.25h11.09q1.117 0 1.863.833q.745.832.621 1.943l-1.611 14.5q-.246 2.224-2.484 2.224H8.066q-2.238 0-2.484-2.224l-1.611-14.5q-.124-1.111.621-1.943q.746-.833 1.863-.833M9.55 6.9q-.086.064-.15.15q-1.65 2.2-1.65 3.45q0 2.25 2.25 2.25t2.25-2.25q0-1.25-1.65-3.45q-.09-.119-.218-.195t-.276-.097t-.292.015t-.264.127m3.85 5.65q-1.65 2.2-1.65 3.45q0 2.25 2.25 2.25q.932 0 1.591-.659T16.25 16q0-1.25-1.65-3.45q-.044-.059-.099-.108q-.055-.05-.119-.087q-.063-.038-.133-.063q-.07-.024-.143-.034t-.147-.007t-.145.022t-.138.051t-.126.076q-.086.064-.15.15");
}

</style>
