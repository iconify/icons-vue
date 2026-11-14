<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seriqilbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dormer-window" /></template>
<style>
.seriqilbi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.75 12.285l-4.886 7.818q-.079.126-.104.273t.009.293q.034.145.12.266q.087.122.214.201q.182.114.397.114h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.215-.114-.397l-4.886-7.818V9q0-.149-.057-.287t-.163-.243l-4.5-4.5q-.105-.106-.243-.163T12 3.75t-.287.057t-.243.163l-4.5 4.5q-.106.105-.163.243T6.75 9zm5-3.035h.5q2.25 0 2.25 2.25V13q0 2.25-2.25 2.25h-.5Q9.5 15.25 9.5 13v-1.5q0-2.25 2.25-2.25m-5 5.865V17.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.385l2.897 4.635H3.853z");
}

</style>
