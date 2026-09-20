<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gep2bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-busy-sharp" /></template>
<style>
.e3gep2bnj {
  fill: currentColor;
  d: path("m9.7 17.758l-.708-.708l2.3-2.3l-2.3-2.3l.708-.708l2.3 2.3l2.3-2.3l.708.708l-2.3 2.3l2.3 2.3l-.708.708l-2.3-2.3zM4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5z");
}

</style>
