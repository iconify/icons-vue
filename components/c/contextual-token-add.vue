<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o04gi1gil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contextual-token-add" /></template>
<style>
.o04gi1gil {
  fill: currentColor;
  d: path("M18 9V7h-2V6h2V4h1v2h2v1h-2v2zM6.77 15.346h5.73v-1.961H6.77zm0-4.73h5.73V8.654H6.77zM4.615 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h9.252q-.123.354-.187.732q-.065.377-.065.768q0 1.1.445 2.026q.446.926 1.21 1.59v5.23h1.96v-4.138q.309.088.623.133q.314.044.647.044q.696 0 1.324-.186q.628-.185 1.176-.507v6.693q0 .69-.462 1.153T19.385 19z");
}

</style>
