<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsopf_b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emergency-share-sharp" /></template>
<style>
.lsopf_b9z {
  fill: currentColor;
  d: path("M12 22.673q-2.486-2.229-3.743-4.111T7 15.15q0-2.127 1.449-3.638T12 10t3.551 1.512T17 15.15q0 1.644-1.305 3.47T12 22.672m.793-6.88q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M8.47 7.143l-.688-.69q.885-.75 1.967-1.159T12 4.884t2.252.41t1.967 1.16l-.688.688q-.744-.628-1.657-.943T12 5.885t-1.874.314t-1.657.943M5.65 4.317l-.694-.707q1.46-1.325 3.277-2.025T12 .885q1.97 0 3.787.7t3.277 2.044l-.708.713q-1.314-1.198-2.945-1.827q-1.63-.63-3.411-.63q-1.761 0-3.399.617T5.65 4.317");
}

</style>
