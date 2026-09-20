<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbm_3rdtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-check-rounded" /></template>
<style>
.mbm_3rdtj {
  fill: currentColor;
  d: path("M15.3 8.825L14.225 7.75q-.15-.15-.35-.137t-.35.162t-.15.35t.15.35L14.6 9.55q.3.3.7.3t.7-.3l2.475-2.5q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15zM4 20q-.425 0-.712-.288T3 19t.288-.712T4 18h10q.425 0 .713.288T15 19t-.288.713T14 20zm8.463-8.462Q11 10.075 11 8t1.463-3.537T16 3t3.538 1.463T21 8t-1.463 3.538T16 13t-3.537-1.463M4 12q-.425 0-.712-.288T3 11t.288-.712T4 10h4.675q.425 0 .713.288t.287.712q0 .4-.288.7t-.712.3zm0 4q-.425 0-.712-.288T3 15t.288-.712T4 14h7.925q.425 0 .713.288t.287.712q0 .4-.275.7t-.725.3z");
}

</style>
