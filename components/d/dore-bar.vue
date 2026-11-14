<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4-e7bbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dore-bar" /></template>
<style>
.d4-e7bbdk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.829 10.665l2.5-5q.047-.094.117-.171t.16-.132t.189-.083Q7.896 5.25 8 5.25h8q.104 0 .205.029q.1.028.189.083t.16.132q.07.077.117.171l2.5 5q.018.036.032.074l.003.009l2.5 7q.044.122.044.252q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.13 0-.252-.044q-.07-.025-.133-.062q-.064-.038-.118-.088q-.055-.05-.099-.109t-.076-.126t-.049-.138t-.022-.146t.007-.147q.011-.073.036-.142l2.5-7q.015-.043.035-.083m12.457-.415l-1.75-3.5H8.464l-1.75 3.5z");
}

</style>
