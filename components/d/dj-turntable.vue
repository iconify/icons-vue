<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjixj2bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dj-turntable" /></template>
<style>
.cjixj2bws {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h12q1.76 0 3.005 1.245T22.25 6v12q0 1.76-1.245 3.005T18 22.25H6q-1.76 0-3.005-1.245T1.75 18V6q0-1.76 1.245-3.005T6 1.75m11.5 2.5q-2.5 0-2.5 2.5q0 2.092 1.75 2.433v3.448l-1.198.921q.198-.735.198-1.552q0-2.382-1.684-4.066T10 6.25T5.934 7.934T4.25 12t1.684 4.066T10 17.75q2.296 0 3.944-1.565q.093.041.193.056q.1.016.201.004t.195-.05t.174-.101l3.25-2.5q.069-.052.123-.119q.055-.066.093-.144t.057-.161t.02-.17V9.183Q20 8.842 20 6.75q0-2.5-2.5-2.5");
}

</style>
