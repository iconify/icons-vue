<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ay9dnxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:decrescendo" /></template>
<style>
.y-ay9dnxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.255 11.295l-18-6.5q-.141-.051-.29-.044t-.284.07t-.235.174q-.101.11-.151.25q-.026.07-.037.143t-.007.147q.003.073.021.145t.049.139t.075.126t.099.109q.054.05.118.088q.063.038.132.063L18.792 12L2.745 17.795q-.069.025-.132.063q-.064.038-.118.088q-.055.05-.099.109t-.075.126t-.049.139t-.021.145q-.004.074.007.147t.037.143q.05.14.151.25q.1.111.235.174t.284.07t.29-.044l18-6.5q.124-.044.225-.128q.101-.085.167-.198l.032-.06q.015-.032.026-.064q.045-.123.045-.253q0-.131-.044-.254l-.001-.003q-.011-.032-.026-.064q-.063-.135-.174-.235q-.11-.101-.25-.151");
}

</style>
