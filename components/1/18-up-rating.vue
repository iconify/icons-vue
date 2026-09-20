<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gofj4g3ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:18-up-rating" /></template>
<style>
.gofj4g3ig {
  fill: currentColor;
  d: path("M8.808 14.692h.884V9.308H7.308v.884h1.5zm3.769 0h2.346q.327 0 .548-.22q.221-.222.221-.549v-3.846q0-.327-.22-.548q-.222-.221-.549-.221h-2.346q-.327 0-.548.22q-.221.222-.221.549v3.846q0 .327.22.548q.222.221.549.221m.115-.769v-1.538h2.116v1.538zm0-2.307v-1.539h2.116v1.539zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
