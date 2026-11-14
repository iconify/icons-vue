<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnng07bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-shading" /></template>
<style>
.tnng07bjq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 8.75h5.315l.438-4.818q.014-.148.083-.281q.069-.132.184-.227q.101-.084.225-.129q.123-.045.255-.045q.034 0 .068.003q.073.007.144.028t.137.055q.065.034.122.081q.058.046.105.103t.083.121q.035.065.057.136q.022.07.03.144t.001.147L9.821 8.75H21q.089 0 .175.021q.086.02.165.061t.147.098t.12.129l-4-5.5q-.053-.072-.12-.129q-.068-.058-.147-.098q-.079-.041-.165-.061q-.086-.021-.175-.021H7q-.089 0-.175.021q-.086.02-.165.061t-.147.098q-.067.057-.12.129l-4 5.5q.053-.072.12-.129q.068-.058.147-.098q.079-.041.165-.061q.086-.021.175-.021m11.018 1.5H9.982L12 17.65zm-2.599 10.724l-.004-.005q-.098-.122-.139-.272L8.427 10.25H3q-.169 0-.321-.072t-.259-.203z");
}

</style>
