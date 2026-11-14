<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1mzssbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fingerprint-brush" /></template>
<style>
.b1mzssbni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.53 6.97l-.469-.47l3.469-3.47q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094L17 5.439l-.47-.469q-.045-.046-.097-.082t-.11-.065q-.057-.027-.119-.045t-.125-.024q-.064-.007-.127-.002q-.064.004-.126.019t-.121.039q-.059.026-.112.06l-4.25 2.75q-.113.073-.193.18q-1.691 2.255.302 4.248t4.248.302q.107-.08.18-.193l2.75-4.25q.034-.053.06-.112t.039-.121q.015-.062.019-.126q.005-.063-.002-.127t-.024-.125q-.018-.062-.045-.119q-.028-.058-.065-.11q-.036-.052-.082-.097M8 14q-6.25 0-6.25 2.5v3.25q0 2.5 6.25 2.5t6.25-2.5V16.5Q14.25 14 8 14m-4.75 5.75v-1.401Q4.812 19 8 19t4.75-.651v1.401q0 1-4.75 1t-4.75-1");
}

</style>
