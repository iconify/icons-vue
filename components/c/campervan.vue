<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4k18xnem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:campervan" /></template>
<style>
.b4k18xnem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 9v8q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.81q-.06.345-.06.75q0 2.75 2.75 2.75t2.75-2.75q0-.405-.06-.75h4.62q-.06.345-.06.75q0 2.75 2.75 2.75t2.75-2.75q0-.405-.06-.75h1.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.5q0-.149-.057-.287t-.163-.243l-5.5-5.5q-.105-.106-.243-.163T16 6.25H4.5q-1.139 0-1.945.805Q1.75 7.861 1.75 9M7 9.25h2q2.25 0 2.25 2.25v.5q0 2.25-2.25 2.25H7q-2.25 0-2.25-2.25v-.5q0-2.25 2.25-2.25");
}

</style>
