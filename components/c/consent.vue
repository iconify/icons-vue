<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivhh9xfsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:consent" /></template>
<style>
.ivhh9xfsh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 4.75h6q3.003 0 5.127 2.123T22.25 12t-2.123 5.127Q18.003 19.25 15 19.25H9q-3.003 0-5.127-2.123T1.75 12t2.123-5.127Q5.997 4.75 9 4.75m5.463 7.403l-.433-.433q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l1 1q.105.106.243.163T14.5 14t.287-.057t.243-.163q.018-.017.034-.036l1.75-2q.099-.112.146-.254q.048-.141.038-.29t-.076-.282t-.178-.232q-.056-.049-.12-.086t-.134-.06t-.143-.034q-.073-.009-.147-.004t-.145.024t-.137.052q-.067.032-.125.077q-.059.046-.107.101z");
}

</style>
