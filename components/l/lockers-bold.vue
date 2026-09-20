<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d-7suqoxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lockers-bold" /></template>
<style>
.d-7suqoxc {
  fill: currentColor;
  d: path("M192 80a12 12 0 0 1-12 12h-16a12 12 0 0 1 0-24h16a12 12 0 0 1 12 12m-12 28h-16a12 12 0 0 0 0 24h16a12 12 0 0 0 0-24M76 92h16a12 12 0 0 0 0-24H76a12 12 0 0 0 0 24m16 16H76a12 12 0 0 0 0 24h16a12 12 0 0 0 0-24m136-60v176a12 12 0 0 1-24 0v-12h-64v12a12 12 0 0 1-24 0v-12H52v12a12 12 0 0 1-24 0V48a20 20 0 0 1 20-20h160a20 20 0 0 1 20 20M116 188V52H52v136Zm24 0h64V52h-64Z");
}

</style>
