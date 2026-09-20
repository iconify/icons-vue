<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orlzkzb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-bishop-sharp" /></template>
<style>
.orlzkzb3k {
  fill: currentColor;
  d: path("M5 21v-4.173q1.414-1.027 2.459-2.402t1.695-2.983H6.846v-1h2.012L6.96 7.192L12 2.02l5.039 5.173l-1.897 3.25h1.992v1h-2.307q.67 1.608 1.714 2.983Q17.587 15.8 19 16.827V21zm7.52-13.364q.21-.21.21-.52t-.21-.52q-.209-.211-.52-.211t-.52.21t-.21.52t.21.52q.209.211.52.211t.52-.21");
}

</style>
