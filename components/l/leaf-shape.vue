<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4pnzelw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-shape" /></template>
<style>
.eg4pnzelw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.753 19.187l8.717-8.717q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-8.717 8.717q6.479-.104 10.905-4.529Q20.25 11.186 20.25 4.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-6.686 0-11.218 4.532q-4.425 4.426-4.529 10.905");
}

</style>
