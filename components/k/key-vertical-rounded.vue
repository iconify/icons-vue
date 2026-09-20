<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5e-sipu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:key-vertical-rounded" /></template>
<style>
.oz5e-sipu {
  fill: currentColor;
  d: path("M13.327 8.308q.539-.539.539-1.308t-.539-1.308t-1.308-.538t-1.307.538T10.173 7t.539 1.308t1.307.538t1.308-.538m-1.6 13.399q-.136-.053-.267-.178l-1.537-1.442q-.111-.106-.17-.24q-.059-.133-.084-.276q-.025-.142.028-.291q.053-.15.14-.28l.932-1.211l-1.05-1.358q-.092-.112-.135-.229t-.043-.26t.043-.26t.116-.228l.82-1.07v-2.85q-1.34-.355-2.285-1.607T7.289 7q0-2 1.365-3.366q1.365-1.365 3.365-1.365t3.366 1.365T16.75 7q0 1.698-.958 2.941t-2.273 1.593v8.7q0 .162-.056.311t-.186.28l-.698.698q-.125.125-.259.18q-.133.057-.295.057t-.298-.053");
}

</style>
