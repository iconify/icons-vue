<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggouzbb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:electrolyser" /></template>
<style>
.ggouzbb6v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 1.75q-2.75 0-2.75 2.75T9.5 7.25t2.75-2.75T9.5 1.75m4 2.75Q13.5 2 16 2t2.5 2.5T16 7t-2.5-2.5m-.97 3.47q4.72 4.719 4.72 8.53q0 2.175-1.538 3.712Q14.175 21.75 12 21.75t-3.712-1.538Q6.75 18.675 6.75 16.5q0-3.811 4.72-8.53q.105-.106.243-.163T12 7.75t.287.057t.243.163");
}

</style>
