<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkvz0wb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-award" /></template>
<style>
.xkvz0wb0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.808 4.388l.456 1.065a1.5 1.5 0 0 0 1.244.903l1.153.105a.879.879 0 0 1 .5 1.537l-.872.763a1.5 1.5 0 0 0-.475 1.461l.257 1.13a.879.879 0 0 1-1.308.95l-.994-.593a1.5 1.5 0 0 0-1.538 0l-.994.593a.879.879 0 0 1-1.308-.95l.257-1.13a1.5 1.5 0 0 0-.475-1.461l-.872-.763a.879.879 0 0 1 .5-1.537l1.153-.105a1.5 1.5 0 0 0 1.244-.903l.456-1.065a.879.879 0 0 1 1.616 0M9.25 17.5h5.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 14.75 21h-5.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M12 14v3.5");
}

</style>
