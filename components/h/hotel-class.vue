<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psmmytbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hotel-class" /></template>
<style>
.psmmytbzd {
  fill: currentColor;
  d: path("m16.7 14.5l3.8-3.25l3 .25l-4.4 3.825L20.4 21l-2.55-1.55zm-2.35-7.3L13.3 4.75L14.45 2l2.3 5.425zM4.325 21l1.625-7.025L.5 9.25l7.2-.625L10.5 2l2.8 6.625l7.2.625l-5.45 4.725L16.675 21L10.5 17.275z");
}

</style>
