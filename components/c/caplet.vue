<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-u-6375g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caplet" /></template>
<style>
.c-u-6375g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.227 4.399L4.399 7.227q-1.245 1.244-1.245 3.005t1.245 3.005l3.181 3.181q-.052-.052-.093-.113t-.069-.13t-.043-.14q-.014-.073-.014-.147q0-.073.015-.146q.014-.072.042-.14t.069-.13t.094-.113l7.778-7.778q.052-.053.113-.094t.13-.069q.068-.028.14-.043t.146-.014q.074 0 .147.014q.072.015.14.043t.13.069t.114.093l-3.182-3.181q-1.244-1.245-3.005-1.245T7.227 4.399m9.193 3.182q.105.106.162.243q.057.138.057.287t-.057.287t-.163.243l-7.778 7.778q-.105.106-.243.163t-.287.057t-.286-.057t-.243-.162l3.181 3.181q1.244 1.245 3.005 1.245t3.005-1.245l2.828-2.828q1.245-1.244 1.245-3.005t-1.245-3.005z");
}

</style>
