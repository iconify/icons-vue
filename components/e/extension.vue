<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oknrkfb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension" /></template>
<style>
.oknrkfb7k {
  fill: currentColor;
  d: path("M5.442 20.116q-.6 0-1.02-.431Q4 19.254 4 18.654V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416V6.23q0-.614.415-1.038q.414-.424 1.008-.424h3.262q.156-1.121.957-1.887q.802-.766 1.916-.766q1.108 0 1.91.766t.963 1.887h3.242q.594 0 1.018.424t.425 1.038v3.485q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.053v3.485q0 .6-.425 1.03q-.424.432-1.018.432z");
}

</style>
