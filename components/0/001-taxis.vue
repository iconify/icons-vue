<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hgwu5n-dw"/><ellipse class="p7x099bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:001-taxis" /></template>
<style>
.hgwu5n-dw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.434 19.954l3.046-1.513l-1.96 11.118m-2 0h4m-11.27.001c-2.033 0-3.391-1.65-3.033-3.684l.662-3.752c.359-2.034 2.298-3.683 4.332-3.683h0c2.035 0 3.393 1.649 3.034 3.683l-.662 3.752c-.358 2.034-2.298 3.683-4.332 3.683m-10.68.001c-2.034 0-3.392-1.65-3.033-3.684l.661-3.752c.36-2.034 2.299-3.683 4.333-3.683h0c2.034 0 3.392 1.649 3.034 3.683l-.662 3.752c-.359 2.034-2.298 3.683-4.333 3.683");
}

.p7x099bnl {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.5px;
  ry: 12px;
}

</style>
