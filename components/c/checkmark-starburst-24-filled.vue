<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9jy6pmcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-starburst-24-filled" /></template>
<style>
.n9jy6pmcq {
  fill: currentColor;
  d: path("M6.347 3.752a2.75 2.75 0 0 1 3.818-1.582l1.283.632a1.25 1.25 0 0 0 1.104 0l1.283-.632a2.75 2.75 0 0 1 3.682 1.253l.073.162l.063.167l.46 1.353c.125.368.414.657.782.782l1.353.46a2.75 2.75 0 0 1 1.581 3.818l-.63 1.282a1.25 1.25 0 0 0 0 1.105l.63 1.283a2.75 2.75 0 0 1-1.581 3.818l-1.354.46a1.25 1.25 0 0 0-.78.782l-.46 1.353a2.75 2.75 0 0 1-3.82 1.581l-1.282-.632a1.25 1.25 0 0 0-1.104 0l-1.283.632a2.75 2.75 0 0 1-3.818-1.581l-.46-1.354a1.25 1.25 0 0 0-.782-.78l-1.353-.46a2.75 2.75 0 0 1-1.582-3.819l.632-1.283a1.25 1.25 0 0 0 0-1.105l-.632-1.282a2.75 2.75 0 0 1 1.582-3.818l1.353-.46a1.25 1.25 0 0 0 .782-.782zM16.28 8.97a.75.75 0 0 0-1.06 0l-4.47 4.47l-1.97-1.97a.75.75 0 0 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5-5a.75.75 0 0 0 0-1.06");
}

</style>
