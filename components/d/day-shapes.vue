<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huk6bibnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:day-shapes" /></template>
<style>
.huk6bibnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5q0-3.25 3.25-3.25T15.25 5q0 2.501-1.924 3.077l2.287 3.24q.067.095.102.206t.035.227t-.035.227t-.102.206l-2.71 3.839l3.23 5.075q.039.063.066.132q.027.068.04.141q.012.073.011.147t-.018.146q-.016.072-.046.139t-.072.128t-.096.112q-.053.051-.115.091q-.185.117-.403.117h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.218.117-.403l3.23-5.075l-2.71-3.839q-.067-.095-.102-.206t-.035-.227t.035-.227t.102-.206l2.287-3.24Q8.75 7.501 8.75 5");
}

</style>
