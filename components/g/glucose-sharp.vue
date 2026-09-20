<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bld1u2b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glucose-sharp" /></template>
<style>
.bld1u2b9f {
  fill: currentColor;
  d: path("m13.28 21l-6.5-7.573l1.69-1.28l3.03 1.932V3.5h1v9h2.173V6.923h1V12.5h2.173V8.116h1V12.5h2.173v-2.384h1V21zM4.5 9.5q-1.263 0-2.132-.859Q1.5 7.783 1.5 6.55q0-.754.29-1.283q.289-.528 1.5-1.896L4.5 1.994l1.19 1.383q1.218 1.398 1.514 1.912q.296.513.296 1.261q0 1.214-.871 2.082T4.5 9.5");
}

</style>
