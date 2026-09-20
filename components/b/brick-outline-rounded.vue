<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0br--b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brick-outline-rounded" /></template>
<style>
.b0br--b3a {
  fill: currentColor;
  d: path("M2 18.5v-9q0-.625.438-1.062T3.5 8H5V5.5q0-.625.438-1.062T6.5 4h3q.625 0 1.063.438T11 5.5V8h2V5.5q0-.625.438-1.062T14.5 4h3q.625 0 1.063.438T19 5.5V8h1.5q.625 0 1.063.438T22 9.5v9q0 .625-.437 1.063T20.5 20h-17q-.625 0-1.062-.437T2 18.5m2-.5h16v-8H4zM7 8h2V6H7zm8 0h2V6h-2zM4 18h16zM7 8h2zm8 0h2z");
}

</style>
