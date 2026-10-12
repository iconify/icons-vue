<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6v4fzrqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gilli-danda" /></template>
<style>
.s6v4fzrqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.53 18.72L13.97 8.28q.53-.53 1.06 0l.94.94q.53.53 0 1.06L5.53 20.72q-.53.53-1.06 0l-.94-.94q-.53-.53 0-1.06M6.25 16L8 17.75m5.74-13.34l1.52-1.07Q15.75 3 16.35 3h2.05q.6 0 1.07.37l1.31 1.01q.47.37 0 .74l-1.31 1.01q-.47.37-1.07.37h-2.05q-.6 0-1.09-.34l-1.52-1.07q-.49-.34 0-.68");
}

</style>
