<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcp9rjbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:encrypted-add-circle-outline" /></template>
<style>
.pcp9rjbhk {
  fill: currentColor;
  d: path("M5 11.1V5.692l7-2.615l7 2.615v4.924h-1V6.38l-6-2.23l-6 2.23v4.72q0 1.317.345 2.548t.967 2.297q.62 1.067 1.464 1.922t1.84 1.43v1.126q-2.483-1.24-4.05-3.753T5 11.1m11.616 8.4h.769v-2.116H19.5v-.769h-2.116V14.5h-.769v2.116H14.5v.769h2.116zM17 21q-1.671 0-2.835-1.164Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21m-3.955-9.962q.436-.424.436-1.036t-.436-1.047t-1.047-.436t-1.036.436t-.424 1.047t.424 1.036t1.036.424t1.047-.424");
}

</style>
