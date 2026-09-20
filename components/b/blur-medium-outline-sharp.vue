<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve0cveb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blur-medium-outline-sharp" /></template>
<style>
.ve0cveb9v {
  fill: currentColor;
  d: path("M15 17H7v-2h4q-.35-.425-.562-.937T10.1 13H4.5v-2h5.6q.125-.55.338-1.062T11 9H4V7h11q2.075 0 3.538 1.463T20 12t-1.463 3.538T15 17m2.125-2.875Q18 13.25 18 12t-.875-2.125T15 9t-2.125.875T12 12t.875 2.125T15 15t2.125-.875M4 17v-2h2v2z");
}

</style>
