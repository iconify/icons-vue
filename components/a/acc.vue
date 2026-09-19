<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uk-tvmbqq"/><circle class="wk3uuub4u"/><circle class="wuh0wjifj"/><circle class="z4y8eteic"/><path class="kfcuqhbmo"/><path class="xleervb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acc" /></template>
<style>
.kfcuqhbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.774 23.416a4.214 4.214 0 0 0-8.017-1.822l-.01-.012s-1.776 3.318-3.666 3.584c.719 1.544 4.057 3.853 8.416 2.365l-.005-.006a4.22 4.22 0 0 0 3.282-4.11");
}

.uk-tvmbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.253 11.903a16.4 16.4 0 0 0-6.966-2.57a16.659 16.659 0 1 0-4.004 33.074a16.9 16.9 0 0 0 5.295-.25a3.803 3.803 0 0 0 1.893-6.41l-1.17-1.17a2.584 2.584 0 0 1 .332-3.932a2.68 2.68 0 0 1 3.417.38l1.602 1.601a3.81 3.81 0 0 0 6.31-1.527a16.7 16.7 0 0 0 .675-7.669a16.4 16.4 0 0 0-2.684-6.907");
}

.wk3uuub4u {
  cx: 17.312px;
  cy: 17.305px;
  r: 2.804px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wuh0wjifj {
  cx: 15.253px;
  cy: 32.905px;
  r: 2.804px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xleervb2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.512 19.304c.885-3.507 13.607-16.15 16.561-13.434s-10.29 15.559-13.475 16.336");
}

.z4y8eteic {
  cx: 12.698px;
  cy: 24.635px;
  r: 2.804px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
