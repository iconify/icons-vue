<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys67mxc2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-bitcoin-outline-rounded" /></template>
<style>
.ys67mxc2o {
  fill: currentColor;
  d: path("M9.808 19.5V18h-2.5q-.214 0-.357-.143t-.143-.357t.143-.357t.357-.143h1.5V7h-1.5q-.214 0-.357-.143T6.808 6.5t.143-.357T7.308 6h2.5V4.5q0-.213.143-.357T10.308 4t.357.143t.143.357V6H13V4.5q0-.213.143-.357T13.5 4t.357.143T14 4.5v1.529q1.32.08 2.16.97T17 9.25q0 .802-.308 1.436q-.307.633-.796 1.043q.99.333 1.547 1.146T18 14.75q0 1.42-.915 2.335q-.916.915-2.335.915H14v1.5q0 .214-.143.357T13.5 20t-.357-.143T13 19.5V18h-2.192v1.5q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357m0-8h3.942q.979 0 1.615-.636Q16 10.23 16 9.25t-.636-1.614Q14.73 7 13.75 7H9.808zm0 5.5h4.942q.979 0 1.615-.636Q17 15.73 17 14.75t-.636-1.614t-1.614-.636H9.808z");
}

</style>
