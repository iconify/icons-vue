<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hu49fub-i"/><path class="s1vjl-b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easyreader" /></template>
<style>
.hu49fub-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.584c1.16-.028 1.412-1.032 2.74-1.7c3.99-2.007 10.901-.542 14.02-.137c1.273.165 2.312-.24 2.578-1.394c.13-.565.12-1.647.12-1.647l.04-18.926c-.037-.15.378-2.104-2.59-2.483C37.793 10.9 27.078 8.8 24 12.963m0 24.621c-1.16-.028-1.412-1.032-2.74-1.7c-3.99-2.007-10.901-.542-14.02-.137c-1.273.165-2.312-.24-2.578-1.394c-.13-.565-.12-1.647-.12-1.647l-.04-18.926c.037-.15-.378-2.104 2.59-2.483C10.208 10.9 20.923 8.8 24 12.963m0 0v24.62m-13.604-9.479h8.633");
}

.s1vjl-b0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.762 21.548a3.5 3.5 0 0 1 1.078 2.525h0c0 .934-.374 1.829-1.038 2.486m1.781-7.256a6.38 6.38 0 0 1 2.143 4.77h0a6.38 6.38 0 0 1-1.634 4.264m1.473-11.476a9.52 9.52 0 0 1 3.304 7.212h0c0 2.272-.812 4.47-2.29 6.195m-25.183-6.921h8.633m-8.633-4.757h8.633");
}

</style>
