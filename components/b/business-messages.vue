<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiv8xp1to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:business-messages" /></template>
<style>
.tiv8xp1to {
  fill: currentColor;
  d: path("M6.942 19q-.728 0-1.22-.462q-.491-.463-.491-1.153V8.846L2 5h17.289q.728 0 1.22.463q.491.462.491 1.153v10.769q0 .69-.491 1.153q-.492.462-1.22.462zm5.654-2.5l.708-.708l-1.754-1.6h5.316v-1h-7.75zm-3.48-5.692h7.75L13.404 7.5l-.708.708l1.754 1.6H9.116z");
}

</style>
