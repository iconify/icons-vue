<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbzfgb_pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-video-outline-sharp" /></template>
<style>
.nbzfgb_pm {
  fill: currentColor;
  d: path("M8.679 19h6.662l-.75-3H9.429zM9 15h6q2.075 0 3.538-1.463T20 10t-1.463-3.537T15 5H9Q6.925 5 5.463 6.463T4 10t1.463 3.538T9 15m1.232-3.235Q9.5 11.029 9.5 9.996t.736-1.764t1.768-.732t1.764.736t.732 1.768t-.735 1.764t-1.769.732t-1.764-.735M6.499 8.73q.31 0 .521-.21q.21-.21.21-.52t-.21-.521q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21M4.5 20v-1h3.148l.756-3.042q-2.283-.214-3.843-1.911T3 10q0-2.507 1.747-4.253Q6.493 4 9 4h6q2.507 0 4.254 1.747Q21 7.493 21 10q0 2.35-1.56 4.047t-3.844 1.91L16.352 19H19.5v1zm9.979-7.521Q15.5 11.458 15.5 10t-1.021-2.479T12 6.5T9.521 7.521T8.5 10t1.021 2.479T12 13.5t2.479-1.021M8.679 19h6.662z");
}

</style>
