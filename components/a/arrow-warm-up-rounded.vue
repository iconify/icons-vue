<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgh2tqb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-warm-up-rounded" /></template>
<style>
.hgh2tqb3m {
  fill: currentColor;
  d: path("M11.643 11.856q-.143-.143-.143-.356V4.864L6.677 9.68q-.14.14-.332.134q-.191-.007-.34-.153q-.138-.135-.138-.342t.14-.347l5.428-5.427q.13-.13.27-.183t.297-.053t.296.053t.268.183l5.446 5.446q.14.136.14.34t-.14.349q-.146.165-.357.156q-.21-.01-.357-.156L12.5 4.883V11.5q0 .213-.144.356t-.357.144t-.356-.144m0 5q-.143-.143-.143-.356v-2q0-.213.144-.356t.357-.144t.356.144t.143.356v2q0 .213-.144.356t-.357.144t-.356-.144m0 4q-.143-.143-.143-.356v-1q0-.213.144-.356t.357-.144t.356.144t.143.356v1q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
