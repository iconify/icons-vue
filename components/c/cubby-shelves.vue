<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvimr469l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cubby-shelves" /></template>
<style>
.lvimr469l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25h11q1.76 0 3.005 1.245T21.75 6.5v11q0 1.76-1.245 3.005T17.5 21.75H17q2.25 0 2.25-2.25v-2.25Q19.25 15 17 15h-1q-2.25 0-2.25 2.25v2.25q0 2.25 2.25 2.25H6.5q-1.76 0-3.005-1.245T2.25 17.5v-11q0-1.76 1.245-3.005T6.5 2.25");
}

</style>
