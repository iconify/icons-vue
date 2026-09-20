<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jug7fee1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fluorescent" /></template>
<style>
.jug7fee1n {
  fill: currentColor;
  d: path("M6 14.089V9.933h12v4.155zm5.5-9.243V2.462h1v2.384zm6.816 2.608l-.708-.708L19.1 5.254l.708.708zM11.5 21.462v-2.385h1v2.385zm7.6-2.693l-1.492-1.492l.708-.708l1.492 1.493zM5.684 7.454L4.193 5.96l.708-.707l1.492 1.492zM4.9 18.769l-.708-.707l1.493-1.493l.707.708z");
}

</style>
