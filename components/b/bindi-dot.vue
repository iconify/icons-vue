<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir99-mivw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bindi-dot" /></template>
<style>
.ir99-mivw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.995 5.495Q7.75 6.74 7.75 8.5t1.245 3.005T12 12.75t3.005-1.245T16.25 8.5t-1.245-3.005T12 4.25T8.995 5.495M5.128 13.09Q8.656 18.5 12 18.5t6.872-5.41q.04-.062.092-.114q.051-.053.112-.095t.129-.071t.14-.044t.147-.016t.146.013q.073.013.141.041q.069.027.131.068q.062.04.114.092q.053.051.095.112t.071.129t.044.14t.016.147t-.013.146q-.013.073-.041.141q-.027.069-.068.131Q16.156 20 12 20t-8.128-6.09q-.082-.125-.109-.272q-.028-.147.003-.293q.031-.145.115-.269q.084-.123.209-.204q.062-.041.131-.068q.068-.028.141-.041t.146-.013q.074.001.147.016q.072.015.14.044t.129.071t.112.095q.052.052.092.114");
}

</style>
