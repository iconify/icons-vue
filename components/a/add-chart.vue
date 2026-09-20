<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw42x-bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart" /></template>
<style>
.pw42x-bog {
  fill: currentColor;
  d: path("M7.23 16.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1zM17.5 8V6h-2V5h2V3h1v2h2v1h-2v2zM5.116 20q-.691 0-1.153-.462T3.5 18.384V5.616q0-.691.463-1.153T5.115 4h9.308v3.462q0 .666.475 1.14t1.14.475H19.5v9.308q0 .69-.462 1.153T17.884 20z");
}

</style>
