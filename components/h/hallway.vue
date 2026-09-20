<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbutaacjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hallway" /></template>
<style>
.rbutaacjc {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h3.269L12 1.885L15.116 5h3.269q.69 0 1.153.463T20 6.616v12.769q0 .69-.462 1.153T18.384 21zM7.5 17.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM10.139 5h3.723L12 3.139z");
}

</style>
