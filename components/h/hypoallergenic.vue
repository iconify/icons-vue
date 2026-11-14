<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idiey0kzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hypoallergenic" /></template>
<style>
.idiey0kzb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.279 1.804l7.5 3q.104.041.191.112q.088.07.151.164q.063.093.096.2t.033.22V11q0 7.654-7.945 11.185q-.146.065-.305.065t-.305-.065Q3.75 18.654 3.75 11V5.5q0-.112.033-.22q.033-.107.096-.2t.151-.164q.087-.071.191-.112l7.5-3q.135-.054.279-.054t.279.054M7.75 15.5q0 .149.057.287t.163.243l.007.007q.105.103.24.158q.136.055.283.055h.002Q16.25 16.249 16.25 8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-7.75 0-7.75 8.25");
}

</style>
