<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu4ew5vmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angle-types" /></template>
<style>
.bu4ew5vmq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.4 5.55l-10.5 14q-.073.097-.112.213q-.038.115-.038.237l.001.029q.003.083.024.164t.061.155t.093.138t.121.114q.097.073.213.112q.115.038.237.038h17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-9.321q-.376-2.671-2.421-4.552q-.104-.095-.234-.146L14.6 6.45q.09-.119.127-.264q.037-.144.015-.292t-.097-.276t-.195-.218q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087t-.099.108M7.656 15.708q.039.051.086.094Q9.306 17.24 9.66 19.25H5z");
}

</style>
