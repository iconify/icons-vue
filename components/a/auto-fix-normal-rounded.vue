<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv-nkl7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-fix-normal-rounded" /></template>
<style>
.xqv-nkl7u {
  fill: currentColor;
  d: path("m19.05 4.95l-1.075-.5Q17.7 4.325 17.7 4t.275-.45l1.075-.5l.5-1.075q.125-.275.45-.275t.45.275l.5 1.075l1.075.5q.275.125.275.45t-.275.45l-1.075.5l-.5 1.075q-.125.275-.45.275t-.45-.275l-.5-1.075ZM5.1 21.7l-2.8-2.8q-.3-.3-.3-.725t.3-.725L13.45 6.3q.3-.3.725-.3t.725.3l2.8 2.8q.3.3.3.725t-.3.725L6.55 21.7q-.3.3-.725.3t-.725-.3Zm9.075-10.475l1.4-1.4l-1.4-1.4l-1.4 1.4l1.4 1.4Z");
}

</style>
