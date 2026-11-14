<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlx0nu89b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hire-recommend" /></template>
<style>
.qlx0nu89b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 21.25q.72 0 1.232-.207q.105.1.239.153q.134.054.279.054h10.994q2.435.019 2.748-2.386l1.246-6.982l.006-.038q.156-1.238-.673-2.171T18.75 8.75h-5V5.5q0-1.952-1.722-2.468q-1.736-.521-2.441.867l-3.414 6.146Q5.609 9.75 4.75 9.75h-.5q-2.5 0-2.5 2.5v6.5q0 2.5 2.5 2.5z");
}

</style>
