<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptfk3ga7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guillotine-cutter" /></template>
<style>
.ptfk3ga7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.867 7.021q.091-.505-.028-.963L21.45 4.1q.119-.09.195-.218t.097-.276t-.015-.292t-.127-.264q-.044-.059-.099-.108q-.055-.05-.119-.087q-.063-.038-.133-.063q-.07-.024-.143-.034t-.147-.007q-.074.004-.145.022q-.072.019-.138.051t-.126.076l-2.541 1.906q-.421-.328-.988-.427q-.922-.16-1.686.381l-8.729 6.183v.001q-.732.519-.666 1.306h-.815q-1.398 0-2.386.989q-.989.988-.989 2.386v1.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375H12.42l5.505-3.774q.774-.531.942-1.455");
}

</style>
