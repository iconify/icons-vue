<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjhdj5bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:inclined-plane-block" /></template>
<style>
.zjhdj5bgu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 18.25q0 1.25 1.25 1.25h15q2.25 0 2.25-2.25V8q0-1.391-1.244-2.012q-1.244-.622-2.356.212l-4.96 3.72q-.115-.487-.44-.92l-1.5-2q-1.5-2-3.5-.5l-2 1.5q-2 1.5-.5 3.5l1.5 2q.325.433.76.68l-3.56 2.67q-.7.525-.7 1.4");
}

</style>
