<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ottwy72lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:geocode" /></template>
<style>
.ottwy72lt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 9.75q0 4.811 7.47 12.28q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.916-.915 1.719-1.79q-.999-1.163-.999-2.74q0-1.76 1.245-3.005T17.5 13.25q.831 0 1.546.277Q20 11.469 20 9.75q0-3.314-2.343-5.657T12 1.75T6.343 4.093T4 9.75m4.5 0q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m9 4.75q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
