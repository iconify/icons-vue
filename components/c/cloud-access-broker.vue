<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5r5d0_lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-access-broker" /></template>
<style>
.o5r5d0_lr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 17.25q-2.175 0-3.712-1.538Q1.75 14.175 1.75 12t1.538-3.712Q4.645 6.93 6.499 6.771q1.797-3.858 6.196-3.439q4.348.414 5.411 4.453q1.581.184 2.753 1.356q1.391 1.391 1.391 3.359q0 .931-.312 1.734q-.082-.044-.169-.08l-3-1.25q-.183-.076-.377-.115T18 12.75t-.392.039t-.377.115l-3 1.25q-.136.056-.262.132q-.127.076-.24.17q-.114.094-.213.203t-.18.232t-.145.255t-.105.274q-.043.141-.064.287T13 16v1.25zm11.288-3.192l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2.25q0 2.709-3.455 4.189q-.141.061-.295.061t-.295-.061q-3.455-1.48-3.455-4.189V16q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25Q17.85 14 18 14t.288.058M15.75 16.5v1.75q0 1.617 2.25 2.678q2.25-1.061 2.25-2.678V16.5L18 15.563zm2.25.417l.544.227q-.5.106-1.044.106h-.3z");
}

</style>
