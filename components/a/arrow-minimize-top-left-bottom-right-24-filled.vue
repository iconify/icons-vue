<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u46vsfb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-top-left-bottom-right-24-filled" /></template>
<style>
.u46vsfb0z {
  fill: currentColor;
  d: path("m21 12.505l.116.007A1 1 0 0 1 21 14.505h-5.084l5.788 5.788l.083.094a1 1 0 0 1-.083 1.32l-.095.083a1 1 0 0 1-1.32-.083l-5.79-5.792l-.001 5.094l-.006.116a1.001 1.001 0 0 1-1.994-.116v-7.504l.007-.117a1 1 0 0 1 .993-.883zM10.497 1.999a1 1 0 0 1 1 1v7.504l-.006.117a1 1 0 0 1-.994.883h-7.5l-.118-.006a1.001 1.001 0 0 1 .117-1.994h5.09L2.289 3.707l-.083-.094a1 1 0 0 1 .083-1.32l.095-.083a1 1 0 0 1 1.32.083l5.794 5.794V2.999l.006-.116a1 1 0 0 1 .993-.884");
}

</style>
