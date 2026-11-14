<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jugm2mbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cidr-block" /></template>
<style>
.jugm2mbma {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 1.75h-2q-1.036 0-1.768.732T1.75 4.25v2q0 2.5 2.5 2.5h2q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5m6.5 0h2q2.5 0 2.5 2.5v2q0 2.5-2.5 2.5h-2q-2.5 0-2.5-2.5v-2q0-2.5 2.5-2.5m-6.5 8.5h-2q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h2q2.5 0 2.5-2.5v-2q0-2.5-2.5-2.5m6.5 0h2q2.5 0 2.5 2.5v2q0 2.5-2.5 2.5h-2q-2.5 0-2.5-2.5v-2q0-2.5 2.5-2.5m3.596 10.882l4.5-8q.037-.064.085-.12t.106-.102q.058-.045.124-.079q.066-.033.137-.053t.145-.026t.147.003t.143.032t.135.059q.13.073.222.191q.092.117.132.261q.04.143.023.292q-.018.148-.091.278l-4.5 8q-.037.064-.085.12t-.106.102t-.124.079t-.137.053t-.145.026q-.073.005-.147-.003q-.073-.009-.143-.032t-.135-.059q-.13-.073-.222-.191q-.092-.117-.132-.261q-.04-.143-.023-.292q.018-.148.091-.278");
}

</style>
