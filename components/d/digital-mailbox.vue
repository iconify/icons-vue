<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfbtmlvih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-mailbox" /></template>
<style>
.cfbtmlvih {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 5.5v9.864l-1.452 3.873q-.048.127-.048.263q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.136 0 .263-.048q.07-.026.132-.065q.063-.039.117-.089t.097-.11t.074-.128q.03-.067.047-.139t.02-.146q.002-.073-.01-.146t-.038-.142l-1.452-3.873V5.5q0-2.75-2.75-2.75H6q-1.139 0-1.945.805q-.805.806-.805 1.945m1.5 0q0-1.25 1.25-1.25h12q1.25 0 1.25 1.25v9.25H4.75zm9.5.25h-4.5q-1.195 0-1.819.571q-.173.081-.286.235q-.115.157-.139.35q-.256.544-.256 1.344v2.5q0 1.036.732 1.768t1.768.732h4.5q1.036 0 1.768-.732t.732-1.768v-2.5q0-.8-.256-1.344q-.024-.193-.139-.35q-.113-.154-.286-.235q-.624-.571-1.819-.571");
}

</style>
