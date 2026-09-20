<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j03mn-9fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-sharp" /></template>
<style>
.j03mn-9fo {
  fill: currentColor;
  d: path("M8.882 20.374q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626m6.264-3.52l.708-.708l-3.354-3.354V8h-1v5.208zM5.908 3.427l.707.707l-3.48 3.481l-.708-.707zm12.184 0l3.481 3.48l-.707.709l-3.481-3.481z");
}

</style>
