<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py-r3-day"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-french-outline-rounded" /></template>
<style>
.py-r3-day {
  fill: currentColor;
  d: path("M5.143 16.356Q5 16.213 5 16V8.308q0-.343.232-.576t.576-.232H10.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H6v3h3.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H6V16q0 .213-.144.356t-.357.144t-.356-.144m8 0Q13 16.213 13 16V8.308q0-.343.232-.576t.576-.232h3.577q.666 0 1.14.475T19 9.115v1.962q0 .664-.463 1.131t-1.118.484h-.461l1.686 3.112q.129.244-.018.47t-.415.226q-.14 0-.252-.071q-.112-.072-.175-.19l-1.932-3.547H14V16q0 .213-.144.356t-.357.144t-.356-.144M14 11.692h3.385q.269 0 .442-.173t.173-.442V9.116q0-.27-.173-.443t-.443-.173H14z");
}

</style>
