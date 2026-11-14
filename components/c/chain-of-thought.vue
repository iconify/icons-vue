<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k03bo6age"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chain-of-thought" /></template>
<style>
.k03bo6age {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 9.25q0 3.5 3.5 3.5h9.5q.034 0 .068-.003q3.497-.318 3.179-3.815q-.287-3.159-3.169-3.205q-1.071-3.623-5.078-3.623q-4.035 0-5.093 3.673Q5.5 6.06 5.5 9.25m1 6.5q0-2.25 2.25-2.25T11 15.75T8.75 18T6.5 15.75m-1.25 1q-1.75 0-1.75 1.75t1.75 1.75T7 18.5t-1.75-1.75m-2.24 3.5H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.25 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T3.76 21t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
