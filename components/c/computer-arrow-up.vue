<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6fzu6b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-arrow-up" /></template>
<style>
.q6fzu6b0v {
  fill: currentColor;
  d: path("M1.77 19.462v-1h20.46v1zm2.846-2q-.691 0-1.153-.463T3 15.846V6.077q0-.69.463-1.153t1.152-.462h14.77q.69 0 1.152.462T21 6.077v9.77q0 .69-.463 1.152t-1.153.463zm6.865-3.193h1V9.575l2.119 2.114l.708-.708l-3.327-3.327l-3.289 3.288l.708.714l2.08-2.081z");
}

</style>
