<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_lwywx2e"/><path class="x4h68jbhs"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-response-time" /></template>
<style>
.l_lwywx2e {
  d: path("M12.737 19.599q-.688.05-1.375-.013q-.686-.062-1.354-.234q-.667-.172-1.299-.449q-.631-.278-1.209-.653l-4 1.5l1.5-4q-.141-.218-.269-.444t-.242-.459q-.114-.234-.213-.474q-.1-.24-.184-.485q-.085-.246-.154-.496t-.123-.504t-.093-.511t-.061-.516q-.022-.258-.029-.518t.002-.519q.009-.26.034-.518q.025-.259.066-.515q.04-.257.097-.51q.056-.254.127-.503q.072-.25.159-.495q.086-.244.188-.484q.101-.239.217-.471t.246-.457t.273-.442q.143-.216.3-.424q.156-.207.325-.405q.168-.197.349-.384t.372-.362t.393-.339t.413-.314q.212-.151.432-.289t.448-.261t.464-.234q.235-.109.477-.205t.489-.175t.498-.145t.506-.115q.243-.047.488-.08t.492-.052q.247-.018.494-.023q.248-.004.495.006t.493.035t.491.063q.244.039.486.091q.241.053.48.12q.238.067.472.148t.462.174t.452.201q.223.108.439.228q.217.12.426.252t.41.277q.201.144.393.3q.192.155.375.322t.356.344t.335.364t.313.382t.291.4q.139.205.266.417q.128.212.243.431t.216.445q.102.225.191.456q.088.231.163.467t.136.475q.061.24.109.483q.047.243.08.488q.032.245.051.492t.023.494t-.006.494t-.035.494M15.5 14.75h5m-5 6.5h5");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4h68jbhs {
  d: path("M16.5 14.75v1l3 4.5v1");
}

</style>
