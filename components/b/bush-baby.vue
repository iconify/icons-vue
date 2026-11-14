<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smgsknbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bush-baby" /></template>
<style>
.smgsknbbm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.038 6.273Q10.411 5.75 12 5.75t2.962.523q-.255-1.072-.076-2.091q.43-2.432 2.864-2.432q2.772 0 2.844 3.296q.055 2.546-1.624 4.51q1.28 1.957 1.28 4.444q0 3.417-2.416 5.834T12 22.25t-5.834-2.416Q3.75 17.417 3.75 14q0-2.487 1.28-4.444q-1.679-1.964-1.624-4.51Q3.478 1.75 6.25 1.75q2.434 0 2.864 2.432q.179 1.019-.076 2.091M5.986 8.352q.088-.094.18-.186q.374-.373.771-.689q.945-1.645.699-3.034Q7.426 3.25 6.25 3.25q-1.304 0-1.344 1.829q-.04 1.82 1.08 3.273m11.848-.186q.092.093.18.186q1.12-1.453 1.08-3.273q-.04-1.829-1.344-1.829q-1.176 0-1.386 1.193q-.246 1.389.699 3.034q.397.316.771.689M9 11.25q-2.75 0-2.75 2.75T9 16.75T11.75 14T9 11.25M12.25 14q0-2.75 2.75-2.75T17.75 14T15 16.75T12.25 14");
}

</style>
