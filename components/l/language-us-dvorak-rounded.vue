<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n72ygynwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-us-dvorak-rounded" /></template>
<style>
.n72ygynwt {
  fill: currentColor;
  d: path("M6 15.5h3.442q.27 0 .442-.173q.174-.173.174-.442v-5.77q0-.269-.173-.442T9.442 8.5H6zm-.192 1q-.348 0-.578-.23T5 15.692V8.308q0-.348.23-.578t.578-.23h3.634q.672 0 1.144.472t.472 1.143v5.77q0 .67-.472 1.143q-.472.472-1.144.472zm10.358 0q-.166 0-.31-.11q-.144-.111-.206-.27l-2.725-7.985q-.073-.239.058-.437q.13-.198.38-.198q.166 0 .281.091q.116.092.177.232l2.535 7.32l2.534-7.32q.062-.14.177-.232q.116-.091.281-.091q.25 0 .38.195t.058.44l-2.725 8.004q-.061.159-.205.26t-.31.101z");
}

</style>
