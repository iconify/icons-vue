<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhqor-s0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:attach" /></template>
<style>
.fhqor-s0q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.53 12.03l-6.5 6.5q-.015.016-.032.031q-1.484 1.318-3.468 1.26q-1.985-.058-3.389-1.462T4.679 14.97q-.058-1.984 1.26-3.468q.015-.017.031-.032l7-7l.018-.018q2.528-2.365 4.977.083q2.448 2.449.083 4.977l-.018.018l-6.5 6.5q-.024.024-.05.046q-1.522 1.27-2.924-.132t-.132-2.924q.022-.026.046-.05l6-6q.105-.106.243-.163T15 6.75t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-5.973 5.973q-.362.458.06.88t.88.06l6.463-6.464q1.362-1.465-.056-2.883t-2.883-.056l-6.975 6.974q-2.17 2.458.156 4.784t4.784.156l6.484-6.484q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243");
}

</style>
