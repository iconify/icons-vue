<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9ob2s4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:artist" /></template>
<style>
.qa9ob2s4g {
  fill: currentColor;
  d: path("M16.08 18.035q-.58-.581-.58-1.42q0-.838.58-1.419t1.42-.58q.316 0 .594.095q.279.095.521.297V9.846H21.5v1.539h-2v5.23q0 .839-.58 1.42q-.581.58-1.42.58t-1.42-.58m-7.703-7.527Q7.5 9.63 7.5 8.385t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877M3.5 18.616v-1.647q0-.625.36-1.161q.361-.537.97-.835q1.455-.698 2.853-1.028t2.817-.33q.858 0 1.626.105t1.51.334q-.707.962-.857 2.209t.419 2.353z");
}

</style>
