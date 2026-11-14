<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dil9hfb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:archive-box" /></template>
<style>
.dil9hfb5f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25h14.5q3 0 3 3q0 2.121-1.5 2.743V18.5q0 2.75-2.75 2.75H6q-2.75 0-2.75-2.75V8.993q-1.5-.622-1.5-2.743q0-3 3-3m0 6v9.25q0 1.25 1.25 1.25h12q1.25 0 1.25-1.25V9.25zm8.5 1.5h-2.5q-2 0-2 2t2 2h2.5q2 0 2-2t-2-2m-3 2q0-.5.5-.5h2.5q.5 0 .5.5t-.5.5h-2.5q-.5 0-.5-.5");
}

</style>
