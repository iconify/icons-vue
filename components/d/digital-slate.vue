<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ng_bbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-slate" /></template>
<style>
.g0ng_bbbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.1 3.114l14.918-1.568q.926-.098 1.651.489q.724.587.822 1.514q.234 2.237-2.003 2.472L4.57 7.589q-.926.098-1.651-.489q-.724-.587-.822-1.514Q1.863 3.349 4.1 3.114M17.5 9h-11q-1.76 0-3.005 1.245T2.25 13.25v4.25q0 1.76 1.245 3.005T6.5 21.75h11q1.76 0 3.005-1.245T21.75 17.5v-4.25q0-1.76-1.245-3.005T17.5 9m-8.75 3.25h6.5q2.5 0 2.5 2.5V16q0 2.5-2.5 2.5h-6.5q-2.5 0-2.5-2.5v-1.25q0-2.5 2.5-2.5");
}

</style>
