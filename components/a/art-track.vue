<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0cf3dtxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:art-track" /></template>
<style>
.a0cf3dtxi {
  fill: currentColor;
  d: path("M3.385 18q-.69 0-1.153-.462t-.463-1.153v-8.77q0-.69.463-1.152T3.384 6h8.77q.69 0 1.153.463t.462 1.153v8.769q0 .69-.462 1.153T12.154 18zm.846-3.23h7.077l-2.139-2.886l-1.9 2.5l-1.4-1.85zM17 18V6h1v12zm4.23 0V6h1v12z");
}

</style>
