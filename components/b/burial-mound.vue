<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0pfe6qlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:burial-mound" /></template>
<style>
.e0pfe6qlg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.375 5.25q.984 0 1.679.696q.696.695.696 1.679v8.25q0 .474-.161.88q.068.008.133.029q.065.02.125.051q.061.032.115.074t.099.093t.081.109t.059.123q.024.063.037.131q.012.067.012.135q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.064.011-.128q.011-.063.033-.124q.021-.061.053-.117q.031-.056.072-.106t.09-.092t.103-.075t.115-.057t.123-.036Q3.38 10.75 9 10.75q5.613 0 6.647 6H17.1q-.1-.387-.1-.875v-8.25q0-2.375 2.375-2.375m-5.256 11.5q-.909-4.5-5.119-4.5t-5.119 4.5z");
}

</style>
