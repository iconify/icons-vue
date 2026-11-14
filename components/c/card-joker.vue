<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-mw2jhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:card-joker" /></template>
<style>
.dx-mw2jhz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 1.75h9q1.76 0 3.005 1.245T20.75 6v12q0 1.76-1.245 3.005T16.5 22.25h-9q-1.76 0-3.005-1.245T3.25 18V6q0-1.76 1.245-3.005T7.5 1.75m4.5 3.5q-1.75 0-1.75 1.75q0 .688.27 1.105q-.637.844-1.459 1.183Q8.674 8.5 7.5 8.5q-1.75 0-1.75 1.75q0 1.593 1.451 1.736q.459 1.996.804 5.097q.007.068.027.134q.02.065.051.126q.032.061.074.116q.042.054.093.1t.11.081q.058.036.122.061q.064.024.132.037q.067.012.136.012h6.5q.069 0 .136-.012q.068-.013.132-.037q.064-.025.122-.061q.059-.035.11-.081t.093-.1t.074-.116t.051-.126q.02-.066.027-.134q.345-3.101.804-5.097q1.451-.143 1.451-1.736q0-1.75-1.75-1.75q-1.174 0-1.561.788q-.822-.339-1.459-1.183q.27-.417.27-1.105q0-1.75-1.75-1.75");
}

</style>
