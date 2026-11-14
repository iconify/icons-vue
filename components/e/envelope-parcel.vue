<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd0mhjbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:envelope-parcel" /></template>
<style>
.jd0mhjbfb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 5.25H7q-1.76 0-3.005 1.245q-.361.361-.617.765q.145-.024.29.009q.144.033.265.118L12 13.082l8.067-5.695q.121-.085.265-.118t.29-.009q-.256-.404-.617-.765Q18.76 5.25 17 5.25m4.121 3.17q-.077.114-.188.193l-8.5 6q-.095.067-.206.102T12 14.75t-.227-.035t-.206-.102l-8.5-6q-.111-.079-.188-.193q-.129.514-.129 1.08v5q0 1.76 1.245 3.005T7 18.75h10q1.76 0 3.005-1.245T21.25 14.5v-5q0-.566-.129-1.08");
}

</style>
