<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1wz-6q_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-smart-wake-outline-sharp" /></template>
<style>
.y1wz-6q_l {
  fill: currentColor;
  d: path("M8.77 13.52q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21t.52-.21m3.75 0q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21t.52-.21m3.75 0q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21t.52-.21m-7.388 6.854q-1.455-.626-2.542-1.713t-1.714-2.542T4 13.001t.626-3.12T6.34 7.34t2.54-1.714T12 5t3.12.626t2.54 1.714t1.713 2.54T20 13t-.626 3.12t-1.714 2.542t-2.54 1.713T12 21t-3.12-.626M5.909 3.427l.707.707l-3.48 3.481l-.708-.707zm12.184 0l3.481 3.48l-.707.709l-3.481-3.481zM12 20q2.906 0 4.953-2.047T19 13t-2.047-4.953T12 6T7.047 8.047T5 13t2.047 4.953T12 20");
}

</style>
