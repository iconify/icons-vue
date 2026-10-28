<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8qdkrbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-search-sharp" /></template>
<style>
.c8qdkrbhg {
  fill: currentColor;
  d: path("M14.361 9.558q1.17 0 1.981-.808t.812-1.977t-.808-1.971T14.37 4t-1.981.804t-.812 1.967t.808 1.975t1.976.812m5.516 3.45l-3.188-3.221q-.502.37-1.088.57t-1.235.2q-1.58 0-2.684-1.104t-1.105-2.684q0-1.586 1.105-2.678T14.366 3t2.683 1.091q1.105 1.092 1.105 2.678q0 .648-.197 1.236q-.198.587-.56 1.074l3.188 3.202zM4 19v-8.5h5.467q.837 1.12 2.12 1.78t2.779.662q.46 0 .91-.065q.449-.065.886-.215L20 16.572V19z");
}

</style>
