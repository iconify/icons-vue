<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydlujz8oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:constellation-search" /></template>
<style>
.ydlujz8oc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.5q-2 0-2 2t2 2t2-2t-2-2M4.5 5q0-2 2-2q.828 0 1.414.586T8.5 5t-.586 1.414T6.5 7q-2 0-2-2m6.75-1.5q0-.078.002-.154l-1.772.332q.27.605.27 1.322q0 .078-.003.154l1.68-.315q-.177-.581-.177-1.339m6.719 2.992l-.748-.898q-.425.627-1.19.914l.748.898q.425-.627 1.19-.914M17.5 9.5q0-2 2-2t2 2t-2 2t-2-2m-13.591.273l.719-1.918q.6.321 1.459.381l-.772 2.061q-.631-.435-1.406-.524M1.5 13q0 .829.586 1.414Q2.671 15 3.5 15t1.414-.586Q5.5 13.828 5.5 13t-.586-1.414Q4.329 11 3.5 11t-1.414.586Q1.5 12.171 1.5 13m19 4.5q0-3-3-3t-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626m-3 1.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
