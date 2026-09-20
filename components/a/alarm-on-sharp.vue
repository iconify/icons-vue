<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbacy4bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-on-sharp" /></template>
<style>
.lbacy4bbh {
  fill: currentColor;
  d: path("m10.95 15.858l4.958-4.958l-.714-.713l-4.244 4.244l-2.144-2.144l-.714.713zm-2.068 4.516q-1.455-.626-2.542-1.714t-1.714-2.542T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626M5.908 3.427l.707.707l-3.48 3.481l-.708-.707zm12.184 0l3.481 3.48l-.707.709l-3.481-3.481z");
}

</style>
