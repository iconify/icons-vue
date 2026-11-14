<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-hh1l8wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heaving-line" /></template>
<style>
.t-hh1l8wz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.091 7.909q.659.659.659 1.591q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-1.553-1.098-2.652Q11.053 5.75 9.5 5.75q-3.75 0-3.75 3.75q0 2.175 1.538 3.712Q8.825 14.75 11 14.75t3.712-1.538Q16.25 11.675 16.25 9.5q0-2.899-2.05-4.95Q12.149 2.5 9.25 2.5T4.3 4.55Q2.25 6.601 2.25 9.5q0 9.5 12.579 9.744q.195.877.872 1.555q.952.953 2.299.953t2.299-.953t.951-2.3q.001-1.345-.951-2.298T18 15.248t-2.299.953q-.672.673-.869 1.542Q3.75 17.512 3.75 9.5q0-2.278 1.611-3.889T9.25 4t3.889 1.611T14.75 9.5q0 3.75-3.75 3.75T7.25 9.5q0-2.25 2.25-2.25q.932 0 1.591.659");
}

</style>
