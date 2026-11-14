<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgkv1ib6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lane-arrow-left" /></template>
<style>
.zgkv1ib6s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.28 5.28L6.811 7.75H14q3.75 0 3.75 3.75V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.25 20v-8.5q0-2.25-2.25-2.25H6.811l2.469 2.47q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T8.75 13t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094L4.47 9.031V9.03q-.099-.098-.155-.225q-.057-.127-.064-.266L4.25 8.5q0-.149.057-.287t.163-.243l3.75-3.75q.105-.106.243-.163T8.75 4t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113");
}

</style>
