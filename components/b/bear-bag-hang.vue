<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixrwo4bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bear-bag-hang" /></template>
<style>
.ixrwo4bak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 2.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 2.926 1.75 3t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h8.75v6h-.75q-.177 0-.335.079q-4.36 2.18-3.975 6.673q.407 4.748 5.81 4.748t5.81-4.748q.385-4.493-3.975-6.673q-.158-.079-.335-.079h-.75v-6h3.939l2.281 2.28q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243l-1.219-1.22H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
