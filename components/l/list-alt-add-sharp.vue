<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpq8vs3xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-add-sharp" /></template>
<style>
.hpq8vs3xq {
  fill: currentColor;
  d: path("M17.423 22.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zm-8.758-6.183q.22-.221.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.221m0-3.77q.22-.22.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.55t.222.547t.549.22t.548-.221m0-3.77q.22-.221.22-.548t-.222-.548t-.549-.22t-.548.221t-.22.549t.222.548t.549.22t.548-.221m2.527 3.721h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zM4 20V4h16v9.94q-.475-.207-1.01-.311q-.536-.104-1.067-.104q-1.193 0-2.229.464q-1.035.463-1.778 1.28h-2.724v1h2.004q-.367.61-.57 1.293T12.423 19q0 .25.026.5t.088.5z");
}

</style>
