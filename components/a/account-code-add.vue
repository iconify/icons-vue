<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of22brh1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-code-add" /></template>
<style>
.of22brh1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.258 18.235q-.183.089-.378.15q-.195.06-.397.09q-.201.029-.405.027t-.406-.035q-.201-.034-.395-.098q-.193-.064-.375-.158q-.181-.093-.346-.213q-.165-.121-.309-.265l-3.992-3.992q-.204-.204-.359-.448q-.155-.243-.253-.515q-.098-.271-.135-.557t-.011-.574l.398-4.375q.01-.114.03-.226q.021-.112.05-.222t.069-.218t.088-.21t.106-.202t.122-.192q.066-.094.139-.181t.154-.168t.168-.154t.181-.139q.093-.065.192-.122q.099-.058.202-.106t.21-.088t.218-.069t.222-.05t.226-.03l4.375-.398q.287-.026.574.011q.286.037.557.135t.515.253t.448.359l3.992 3.992q.141.141.259.301q.117.16.21.336t.157.364q.065.188.1.384t.042.394q.006.199-.018.397q-.024.197-.078.389q-.054.191-.136.372M8.275 8.275h.01m4.056 1.238l2.475 2.474M18 15v6m-3-3h6");
}

</style>
