<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aliq-zb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-off-rounded" /></template>
<style>
.aliq-zb7j {
  fill: currentColor;
  d: path("M10.799 20.691q-.51-.462-.607-1.152h3.616q-.096.69-.607 1.152T12 21.154t-1.201-.463m5.805-6.63L7.427 4.859q.987-.912 2.116-1.385T12 3q2.721 0 4.61 1.89T18.5 9.5q0 1.506-.538 2.605t-1.358 1.956m-3.3.939H8.558q-1.417-.929-2.238-2.356T5.5 9.5q0-.52.091-1.08q.092-.562.236-.897L3.023 4.708q-.14-.14-.153-.342q-.012-.2.153-.366q.16-.16.354-.16t.354.16l16.077 16.077q.146.146.156.344q.009.198-.156.364q-.166.165-.357.165t-.357-.165zM9 17.77q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.144h6.035q.213 0 .356.144t.144.356t-.144.357t-.356.143z");
}

</style>
