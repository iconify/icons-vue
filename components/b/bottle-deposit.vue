<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ajkac4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bottle-deposit" /></template>
<style>
.n5ajkac4z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 1.75h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.273l1.874 2.811q.126.189.126.416v10.5q0 2.25-2.25 2.25H6q-2.25 0-2.25-2.25V9q0-.227.126-.416L5.75 5.773V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014M18 12.25q-3.75 0-3.75 3.75T18 19.75T21.75 16T18 12.25");
}

</style>
