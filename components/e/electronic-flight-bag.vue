<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5ysm81k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:electronic-flight-bag" /></template>
<style>
.zj5ysm81k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.625 2.25h-5.25q-2.123 0-3.624 1.501T4.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h5.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T14.625 2.25M12.5 7.5q0-2 2-2t2 2t-2 2q-.825 0-1.31-.341q-.891.372-.969.812q-.063.361.462 1.438q.729 1.494.566 2.305q-.228 1.136-1.789 1.758q.04.244.04.528q0 2-2 2t-2-2t2-2q.633 0 1.065.2q1.127-.348 1.214-.781q.063-.314-.444-1.353q-.739-1.514-.591-2.355q.209-1.189 1.77-1.889q-.014-.154-.014-.322");
}

</style>
