<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o5qbl2iwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-20-filled" /></template>
<style>
.o5qbl2iwq {
  fill: currentColor;
  d: path("M15.66 2.122a.75.75 0 0 1 .34.628v5.5a.75.75 0 0 1-.75.75H2.75a.75.75 0 0 1-.302-1.436l12.5-5.5a.75.75 0 0 1 .712.058M6.317 7.5H14.5V3.9zM16 17.5a.5.5 0 0 1-.71.454l-13-6A.5.5 0 0 1 2.5 11h13a.5.5 0 0 1 .5.5z");
}

</style>
