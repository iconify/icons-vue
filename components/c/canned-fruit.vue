<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqrb7pkhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canned-fruit" /></template>
<style>
.bqrb7pkhg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5q0-2.75 7.75-2.75T19.75 5v14q0 2.75-7.75 2.75T4.25 19zm1.5 1.887V19q0 1.25 6.25 1.25T18.25 19V6.887q-1.91.863-6.25.863t-6.25-.863m5.868 3.378q1.534-1.873 3.677-.954q.068.029.129.071t.113.094q.051.053.092.115q.04.062.067.13q.028.069.041.142t.013.146t-.016.146t-.045.14q-.032.075-.079.141q-.378.529-.795.878q.096.087.19.181Q16.25 12.74 16.25 14.5t-1.245 3.005T12 18.75t-3.005-1.245T7.75 14.5t1.245-3.005q1.107-1.108 2.623-1.23");
}

</style>
