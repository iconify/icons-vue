<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_1d5b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:armored-transport" /></template>
<style>
.l8_1d5b1h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 4.75h6.75q3.182 0 3.364 3H18.5q.164 0 .313.069q.15.068.256.193l3 3.5q.088.102.134.228t.047.26v4.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.438q.188.531.188 1.25q0 2.75-2.75 2.75t-2.75-2.75q0-.719.188-1.25H14.5q-.105 0-.205-.029q-.101-.028-.19-.083t-.159-.133t-.117-.171q-.769.416-1.954.416H9.562q.188.531.188 1.25q0 2.75-2.75 2.75T4.25 18.5q0-.744.202-1.287q-2.702-.318-2.702-3.338v-5.75q0-3.375 3.375-3.375m1.214 2.707Q4.75 7.946 4.75 9.608v1.653q0 1.108.878 1.783l1.75 1.346q1.372 1.057 2.744 0l1.75-1.346q.878-.675.878-1.783V9.608q0-1.662-1.589-2.151l-1.749-.538q-.662-.203-1.323 0zM20.75 15.75v-3.473L18.155 9.25H15.25v4.625q0 1.125-.375 1.875z");
}

</style>
