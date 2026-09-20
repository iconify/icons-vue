<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":192};
const content = `<path class="r63qlvx5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:crateio" /></template>
<style>
.r63qlvx5j {
  fill: var(--svg-color--009dc7, #009dc7);
  d: path("M192 64V0h-64v64H0v64h64v64h64v-64h128V64z");
}

</style>
