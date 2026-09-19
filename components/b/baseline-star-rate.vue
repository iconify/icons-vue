<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9zpsq08m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-star-rate" /></template>
<style>
.j9zpsq08m {
  fill: currentColor;
  d: path("M14.43 10L12 2l-2.43 8H2l6.18 4.41L5.83 22L12 17.31L18.18 22l-2.35-7.59L22 10z");
}

</style>
