<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfe0zknds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:casserole-dish" /></template>
<style>
.rfe0zknds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.797 10.25h8.406q-.402-3-4.203-3t-4.203 3m9.921 0H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.75V15q0 2.382-1.684 4.066T15 20.75H9q-2.382 0-4.066-1.684T3.25 15v-3.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 11.074 1.75 11t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.782q.395-4.5 5.718-4.5t5.718 4.5");
}

</style>
