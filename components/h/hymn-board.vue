<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snenucbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hymn-board" /></template>
<style>
.snenucbvc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 1.75H7q-1.76 0-3.005 1.245T2.75 6v6.75q0 1.76 1.245 3.005T7 17h4.25v4.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V17H17q1.76 0 3.005-1.245t1.245-3.005V6q0-1.76-1.245-3.005T17 1.75M9.25 4.5q2.25 0 2.25 2.25T9.25 9h-1.5Q5.5 9 5.5 6.75T7.75 4.5zm5.5 0h1.5q2.25 0 2.25 2.25T16.25 9h-1.5Q12.5 9 12.5 6.75t2.25-2.25m-5.5 5.25q2.25 0 2.25 2.25t-2.25 2.25h-1.5Q5.5 14.25 5.5 12t2.25-2.25zm6.25 0h.75q2.25 0 2.25 2.25t-2.25 2.25h-.75q-2.25 0-2.25-2.25t2.25-2.25");
}

</style>
