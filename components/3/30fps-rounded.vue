<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2d2sobdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:30fps-rounded" /></template>
<style>
.p2d2sobdj {
  fill: currentColor;
  d: path("M8 19H3.5q-.625 0-1.062-.437T2 17.5t.438-1.062T3.5 16H8v-2.5H3.5q-.625 0-1.062-.437T2 12t.438-1.062T3.5 10.5H8V8H3.5q-.625 0-1.062-.437T2 6.5t.438-1.062T3.5 5H8q1.25 0 2.125.875T11 8v1.9q0 .875-.612 1.488T8.9 12q.875 0 1.488.613T11 14.1V16q0 1.25-.875 2.125T8 19m7-3h4V8h-4zm0 3q-1.25 0-2.125-.875T12 16V8q0-1.25.875-2.125T15 5h4q1.25 0 2.125.875T22 8v8q0 1.25-.875 2.125T19 19z");
}

</style>
