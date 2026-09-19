<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="eu3ma113a"/><path class="zvccajbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwgt" /></template>
<style>
.eu3ma113a {
  width: 8.21px;
  height: 39px;
  x: 10.173px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.642px;
}

.zvccajbej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.006 4.5h-.821a6.57 6.57 0 0 0-6.569 6.568v4.358a.82.82 0 0 1-.269.608l-7.426 6.75a1.64 1.64 0 0 0 0 2.43l7.427 6.752a.82.82 0 0 1 .268.608v4.357a6.57 6.57 0 0 0 6.569 6.569h.82a.82.82 0 0 0 .822-.821V29.606a1.64 1.64 0 0 0-.481-1.16L33.48 24.58a.82.82 0 0 1 0-1.162l3.865-3.864a1.64 1.64 0 0 0 .48-1.161V5.32a.82.82 0 0 0-.82-.821");
}

</style>
