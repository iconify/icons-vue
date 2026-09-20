<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2rkgbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-post-office-rounded" /></template>
<style>
.ah2rkgbos {
  fill: currentColor;
  d: path("M3.77 21q-.31 0-.54-.23T3 20.23v-6.46q0-.31.23-.54t.54-.23H7V8q0-2.077 1.462-3.538T12 3h4q2.077 0 3.539 1.462T21 8v12.5q0 .214-.143.357T20.5 21t-.357-.143T20 20.5V18h-5v2.23q0 .31-.23.54t-.54.23zM9 16.85l-4.336-2.47q-.222-.128-.443 0q-.221.13-.221.382q0 .123.061.224t.16.162l4.375 2.504q.187.106.404.106t.404-.106l4.375-2.504q.098-.061.16-.162t.061-.224q0-.252-.221-.381t-.442 0zm6 .15h5V8q0-1.65-1.175-2.825T16 4h-4q-1.65 0-2.825 1.175T8 8v5h6.23q.31 0 .54.23t.23.54zm-4-7.5q-.213 0-.357-.143T10.5 9t.143-.357T11 8.5h6q.214 0 .357.143T17.5 9t-.143.357T17 9.5z");
}

</style>
