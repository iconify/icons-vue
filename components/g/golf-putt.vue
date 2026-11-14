<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw1kf7b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-putt" /></template>
<style>
.hw1kf7b1v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.995 4.995Q2.75 6.24 2.75 8t1.245 3.005T7 12.25t3.005-1.245T11.25 8t-1.245-3.005T7 3.75T3.995 4.995M16.25 13q0-4.602-2.837-5.232q-.072-.016-.146-.018t-.147.011t-.141.04t-.132.066q-.062.04-.115.091t-.096.112t-.072.128t-.046.139t-.018.146t.011.147t.04.141t.066.132q.04.062.091.115t.112.096t.128.072t.139.046q1.663.37 1.663 3.768q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-7 5.5q0-3.25 6.25-3.25t6.25 3.25t-6.25 3.25t-6.25-3.25");
}

</style>
