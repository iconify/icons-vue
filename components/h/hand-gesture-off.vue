<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ngfnd4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hand-gesture-off" /></template>
<style>
.y6ngfnd4z {
  fill: currentColor;
  d: path("m9 6.208l-1-1v-.15q0-.214.143-.357t.357-.143t.357.143t.143.357zm3.673 3.673l-1-1V3.058q0-.214.143-.357t.357-.143t.357.143t.143.357zM11.171 21.5q-.61 0-1.138-.32q-.53-.32-.939-.769L3.187 13.9l.355-.287q.374-.35.9-.424q.527-.076.975.18L8 14.798V9.421L1.887 3.308l.713-.714l19.223 19.223l-.713.714l-2.12-2.12q-.48.491-1.11.79t-1.38.299zM21.404 5.64q0-1.102-.77-1.87q-.768-.77-1.87-.77v-.885q1.47 0 2.498 1.027t1.027 2.499zM6.058 21.77q-1.594 0-2.711-1.117t-1.116-2.71h.885q0 1.218.861 2.08t2.08.861zM20 17.207l-5.673-5.667h1.02V4.058q0-.214.143-.357t.356-.143t.357.143t.143.357v7.483H19V5.5q0-.213.143-.357T19.5 5t.357.143T20 5.5z");
}

</style>
