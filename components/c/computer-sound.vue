<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqpbyhbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-sound" /></template>
<style>
.bqpbyhbxx {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16.175L15 8.175V12.8l5.175 5.2zm-3 3v-2h22v2zm19.775-5.2l-1.4-1.4q.8-.8 1.213-1.8T21 10.5t-.412-2.1t-1.213-1.8l1.4-1.4q1.075 1.05 1.65 2.425T23 10.5t-.575 2.875t-1.65 2.425m-2.45-2.45l-1.45-1.45q.3-.275.463-.637t.162-.763t-.162-.763t-.463-.637l1.45-1.45q.575.575.875 1.312t.3 1.538t-.3 1.537t-.875 1.313");
}

</style>
