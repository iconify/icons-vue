<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr69dxbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fruit-pieces-pot" /></template>
<style>
.dr69dxbxa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 5.5q0-3.75 3.75-3.75t3.75 3.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T15 6.25H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 5.5M7.5 7.25q3.354 0 3.708 3h1.584q.354-3 3.708-3t3.708 3h.292q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .066-.011.13l-1.49 8.439q-.034 2.181-2.249 2.181h-11q-2.215 0-2.249-2.181l-1.49-8.439q-.026-.147.007-.292q.032-.146.118-.268t.211-.202t.273-.107q.064-.011.13-.011h.292q.354-3 3.708-3m2.174 3q-.337-1.5-2.174-1.5t-2.174 1.5zm6.826-1.5q1.837 0 2.174 1.5h-4.348q.337-1.5 2.174-1.5");
}

</style>
