<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad6d5tggb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-sharp" /></template>
<style>
.ad6d5tggb {
  fill: currentColor;
  d: path("M4 20V4h6.316q-.137-.766.366-1.383Q11.184 2 12.01 2t1.328.617T13.685 4H20v16zm3.5-3.73h6v-1h-6zm0-3.77h9v-1h-9zm0-3.77h9v-1h-9zm5.038-4.5q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212");
}

</style>
