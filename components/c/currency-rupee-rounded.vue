<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a464a6tzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-rupee-rounded" /></template>
<style>
.a464a6tzp {
  fill: currentColor;
  d: path("m13.406 19.854l-5.727-5.977q-.087-.086-.133-.197q-.046-.11-.046-.253v-.388q0-.272.191-.463q.192-.191.463-.191H10.5q1.517 0 2.759-.959t1.268-2.734H7q-.213 0-.357-.143T6.5 8.192t.143-.357T7 7.693h7.42q-.31-1.183-1.388-1.937Q11.954 5 10.5 5H7q-.213 0-.357-.143T6.5 4.5t.143-.357T7 4h10q.214 0 .357.143t.143.357t-.143.357T17 5h-3.442q.715.425 1.24 1.146t.656 1.546H17q.214 0 .357.144t.143.356t-.143.357t-.357.143h-1.467q-.008 2.125-1.52 3.409q-1.511 1.284-3.513 1.284H8.602l5.523 5.761q.239.245.11.55q-.127.304-.47.304q-.104 0-.195-.036q-.091-.037-.164-.11");
}

</style>
